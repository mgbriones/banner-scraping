# Scraping de Cursos UC

## Iniciativa
En la universidad los cupos a los cursos que una persona quiere ingresar suelen estar disponibles en https://buscacursos.uc.cl/. El sistema de toma de cursos suele tomar dos dias, en los cuales, el primer dia solo se es posible tomar un maximo de 3 cursos, para luego el segundo dia tomar los que falten. 

El problema que siempre se tiene en estos casos es el de saber a que cursos dar prioridad en la toma para evitar quedarse sin cupos el segundo dia.

Para esto los estudiantes tienen que revisar constantemente la pagina para saber si quedan o no cupos disponibles.

## Solución
El propocito de este proyecto es poder automatizar ese proceso, de modo que el codigo pueda averiguar a cada instante cuantos cupos quedan, y avisa via mail si a cambiado la cantidad de cupos. De esta forma es posible saber si hay apuro en tomar dicho curso.

## Librerias
Se utilizó:

1) BeautifulSoup: Para hacer el web scraping
2) smtplib: Para enviar correos de notificación