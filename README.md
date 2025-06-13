# FacturaPlant Project

Hey, ¿qué tal a todo? Hoy es traigo mi primer proyecto por el momento llamado FacturaPlant, como os podéis imaginar es algo relacionado con facturas y plantas, pues estás en lo correcto. 

El proyecto consiste en una aplicación web que permita crear facturas de manera sencilla y rápida para empresas agrícolas, la principal diferencia entre un programa de facturación normal y uno específico para el sector agrícola es el Pasaporte Fitosanitario, seguramente no sabréis lo que es normal, el pasaporte fitosanitario es un documento que debe estar adjunto siempre junto a cualquier factura en la que se venda algún tipo de planta, o producto agrícola.

![enter image description here](https://www.aenverde.es/wp-content/uploads/2019/12/pasaporte-fitosanitario.jpg)
Y algunas características más genéricas como gestión de clientes, productos, facturas y además poder exportar las facturas en PDF. Por temas de seguridad no os puedo mostrar el proyecto, pero os pongo aquí las tecnologías que he usado

# Tecnologías

Las tecnologías que he usado para este proyecto son Astro para el frontend, un framework web muy sencillo de usar, ha sido mi primer proyecto con Astro por lo que tuve varias complicaciones que no describire.
![enter image description here](https://cdn.buttercms.com/xrVbfdR5TBy4iTaY4xl7)
Luego use como base de datos una instancia de MySQL, una base de datos muy sencilla de usar y que he trabajado con ella anteriormente por lo que fue la opción idónea
![enter image description here](https://www.ovhcloud.com/sites/default/files/styles/large_screens_1x/public/2021-09/ECX-1909_Hero_MySQL_600x400@2x-1_0.png)
Ahora sé que existen varias maneras de crear PDF, pero la opción más sencilla que encontré es usar wkhtmltopdf un software open-source que sirve para convertir HTML a PDF, por lo que me permitía rellenar una plantilla de una factura html con los datos de la factura, y luego convertirla a PDF 
![enter image description here](https://ourcodeworld.com/public-media/articles/articleocw-590c895c5d17d.png)
