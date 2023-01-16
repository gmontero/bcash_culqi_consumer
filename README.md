**Estructura Base para Proyectos Rabbit**
=========================================

**Actualizacion RVM**
Para instalar la version 3.1.0 de ruby, puede que se genere un error debido a la falta de actualizacion del rvm.
Usar los siguientes comandos para actualizar.
```
sudo apt-get install libmysqlclient-dev
rvm get head
```

**Instalacion** 
```
rvm install 3.1.0
gem install bundle
bundle install
```


**Modo Development** 

Iniciar: `sh rabbit_service.sh start development`

Detener: `sh rabbit_service.sh stop development`

Actualizar: `sh rabbit_service.sh restart development`

Estado: `sh rabbit_service.sh status`


**Modo Produccion** 

Iniciar: `sh rabbit_service.sh start production`

Detener: `sh rabbit_service.sh stop production`

Actualizar: `sh rabbit_service.sh restart production`

Estado: `sh rabbit_service.sh status`
