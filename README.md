# Universidad Técnica Particular de Loja
**Sistemas Basados en el Conocimiento**
**Título del Proyecto: Rocket Engine**
**Estudiante: Renato Balcázar**
**Periodo: Abril - Agosto 2022**
**Profesor: Nelson Piedra**

# Rocket Engine
Este proyecto se basa en un buscador de entidades, consta de dos partes, el frontend y el backend. Como frontend se crea una aplicación móvil en Android utilizando Jetpack Compose y como backend se crea una api en Flask que hace procesamiento de lenguaje natural con FRED y consulta sobre Dbpedia.

# Rocket Engine App - Frontend
Esta es la parte de interfaz del proyecto. Aqui se 


![image](https://user-images.githubusercontent.com/35740463/182888432-3888305a-0407-453b-9fe9-7a2c6ffbe98c.png)
![image](https://user-images.githubusercontent.com/35740463/182888643-15d55704-11f2-406a-bb3d-bda719ccf481.png)
![image](https://user-images.githubusercontent.com/35740463/182888997-ba9d5a1f-6c7a-4d5e-9072-6dc1b054cd78.png)
# engine - Backend
El backend tiene dos principales endpoints:
/annotate
Este endpoint realiza un procesado de lenguaje natural y para cada entidad encontrada realiza una consulta en Dbpedia.


/rdf
Este endpoint realiza una consulta de la entidades obtenidas como json y devuelve una ontología creada usando la api de FRED.
![image](https://user-images.githubusercontent.com/35740463/182893672-754b947c-3449-429a-a91a-219d6deecf1a.png)
![image](https://user-images.githubusercontent.com/35740463/182893866-c5ca330b-1162-453c-b756-47c0795e29e1.png)
![image](https://user-images.githubusercontent.com/35740463/182893957-0c945bea-8e5c-4738-8ce7-8ad235a88ba2.png)
