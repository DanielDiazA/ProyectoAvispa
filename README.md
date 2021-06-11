# Proyecto Avispa 
## [APP SHINY](https://danieldiaz.shinyapps.io/RetoKopuru/)
Proyecto para predecir nuevos nidos de avispas asiáticas en los municipios bizkainos

![](https://www.latiendadelapicultor.com/blog/wp-content/uploads/2015/10/vespa_velutina1.jpg)

### Datos Utilizados

- Frutales Declarados
- Apicultura
- Colmenas
- Datos Brutos de Estaciones Meteorológicas 
- Localización Estaciones Meteorologicas
- Mapa Foresta CAE
- Poblacion
- Nidos de Vespa Velutina 

### Esquema de los Scripts del Proyecto

+  Creacion Tabla Maestra
    + Forestal -> Limpieza Y union de los mapas forestales CAE 2017/2018/2019
    + Frutales -> Limpieza y Union de los Frutales
    + Poblacion -> Limpieza u Union de la Población de cada Municipio de Bizkaia por año
    + Temperaturas -> Limpieza y union de los datos climatologicos de las estaciones meteorologicas de Bizkaia
    + Cambio de Nombre -> Cambio de nombre de las Columnas
    + Union -> Union de los resultados obtenidos en todos los Scripts 
    + extra(primeros predictivos) -> Script con las primeras predicciones 
+  APP Shiny
    + app -> Script con la App mediante shiny
    + Global -> Librerias globales para ejecucion del script en la nube
+  Predicción
    * prediccion -> Script con el que hemos hecho las diferentes entregas en el reto (Xgboost mejores resultados)
  
   
![](https://github.com/DanielDiazA/ProyectoAvispa/blob/main/APP.PNG?raw=true)


