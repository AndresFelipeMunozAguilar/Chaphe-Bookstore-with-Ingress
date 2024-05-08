# Chaphe-Bookstore-with-Ingress

<p align='justify'>Este repositorio contiene los archivos que se van a usar para realizar el despliegue del microservicio "Bookstore-App" de Chaphe, haciendo uso de Ingress, Kubernetes y Microk8s. Este consiste en utilizar la tecnología Ingress para realizar un manejo óptimo de las conexiones entre disntintas direcciones IP de los Pods pertenecientes a un servicio. Este manejo se realiza a través de un mapeo de direcciones IP basado en rutas de nombres de dominio (Ejemplo: "Servicio.app.com") que conducen, las peticiones externas al clúster, a direcciones IP internas, aprovechando los puertos de tipo "NodePort" que el clúster haya asignado internamente a sus respectivos Pods, con el propósito de exponer el servicio al exterior. <br>
Este taller está pensado para ser ejecutado a través de docker Desktop y Kubernetes
</p>

## Organización
* La carpeta "source" contienen los archivos a los cuales se accederán para hacer el deployment mediante archivos YAML
* La carpeta "DeploymentFiles" contiene los archivos YAML (Yet Another Markup Language) mediante los cuales se accederá a los archivos en source para aplicarlos en un cluster remoto y hacer el despliegue de la aplicación. Esta carpeta, también contiene los archivos ingress usados para el despliegue
* La carpeta "Ingress" posee los archivos creados para la adminsitración y el deployment del ingress con nginx. Desde aquí se puede ver el manifiesto de versiones, para versionamiento y, además, el archivo de deployment que permite hacer el despliegue para usar ingress para el enrutamiento de los servicios

## Creadores
Andrés Felipe Muñoz Aguilar - 2210087 \
Marisol Osma Llanes – 2211466

### Referencias
* INSERT LINK
