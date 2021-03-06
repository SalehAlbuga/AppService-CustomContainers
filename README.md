# Azure App Service custom Docker images
Azure App Service custom Docker image samples/boilerplates with different languages &amp; setups including the basic App Service setup (SSH and ports)

**Currently:**

* Node image with a cronjob
* Node image with a custom locale
* Basic Node image with Express
* Basic Ruby image with Rails
* Python image image with Flask & Gunicorn
* VueJs App image
* React App image
* Angular App image
* Static site served with Nginx image

## To deploy an image to App Service
* Build the image with `docker build -t <your_container_registry>/<image_name> .` (notice the **.** at the end)
* Push it to your registry with `docker push <your_container_registry>/<image_name>`
* In your **Linux Web App**, go to **Container Settings** and set the image.

