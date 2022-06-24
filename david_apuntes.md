# Hola SERGIO!
## Modificaciones pendientes
### 1. Archivos  
* _index.html_
* _descargas.html_
* _styles.css_
### 2. Cambios
* En <descargas.html> no existe la carpeta **_img/calendarios/_**
* En los estilos [ ! → Nada grave, !! → Corregir pronto ]:
  * [!] Nunca se utilizan los selectores: {"color-primario", "color-oscuro"}
  * [!!] Los valores expresados en pixeles (px) utilizando decimales ("float values") podrían resultar distintos dependiendo del navegador

## 😡 Parece que el IDE no lanza error por loading="lazy" después del atributo class; sin embargo, solo se debe utilizar en etiquetas < img > (y estas deberán ¡por supuesto!, ir dentro de un < picture >)
## 😡 Al pre-cargar con < link > fuentes y otros recursos externos 'modernos', cuando esto involucra la descarga de varios archivos, se debe incluír la propiedad << crossorigin >>; esta indica que la fuente de cada archivo necesariamente ha de ser la misma (la especificada por la propiedad hyper-reference)