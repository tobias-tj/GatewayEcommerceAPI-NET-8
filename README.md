# Gateway de la API para Ecommerce

Este repositorio contiene el Gateway para la API del proyecto de Ecommerce. El Gateway se encarga de manejar las solicitudes entrantes y enrutar las mismas a los diferentes microservicios de la arquitectura.

![Diagrama de Arquitectura](https://media.licdn.com/dms/image/v2/D4D22AQGN_VQWZFlqTg/feedshare-shrink_1280/feedshare-shrink_1280/0/1724022011622?e=1727913600&v=beta&t=WNzfVfz1ABeewjjOIfiU8PV67AgEHP2NIN4y-uTNpCc)

## Repositorios Necesarios

1. **Autenticación (AuthenticationEcommerceAPI-NET-8)**  
   Este microservicio gestiona la autenticación y autorización de los usuarios en el sistema.  
   - Repositorio: [AuthenticationEcommerceAPI-NET-8](https://github.com/tobias-tj/AuthenticationEcommerceAPI-NET-8)

2. **Gestión de Productos (ProductEcommerceAPI-NET-8)**  
   Este microservicio gestiona la información relacionada con los productos disponibles en el Ecommerce.  
   - Repositorio: [ProductEcommerceAPI-NET-8](https://github.com/tobias-tj/ProductEcommerceAPI-NET-8)

3. **Gestión de Pedidos (OrderEcommerceAPI-NET-8)**  
   Este microservicio gestiona los pedidos realizados por los usuarios en la plataforma.  
   - Repositorio: [OrderEcommerceAPI-NET-8](https://github.com/tobias-tj/OrderEcommerceAPI-NET-8)

4. **Colección de Postman (PostmanEcommerceAPICollection)**  
   La colección de Postman incluye todas las solicitudes necesarias para interactuar con la API.  
   - Repositorio: [PostmanEcommerceAPICollection](https://github.com/tobias-tj/PostmanEcommerceAPICollection)

## Configuración

1. **Clonar los Repositorios**  
   Clona cada uno de los repositorios mencionados anteriormente en tu entorno local.

2. **Configuración del Gateway**  
   - Asegúrate de que las URLs y puertos configurados en el Gateway correspondan a los microservicios clonados.
   - Configura las variables de entorno necesarias, como las claves de API y cadenas de conexión a la base de datos.

3. **Despliegue de Microservicios**  
   - Despliega cada microservicio por separado asegurándote de que cada uno esté operativo antes de iniciar el Gateway.

## Ejecución

Una vez configurados y desplegados todos los microservicios, puedes iniciar el Gateway para que enrute las solicitudes correctamente.

## Licencia

Este proyecto está bajo la Licencia [MIT](LICENSE).

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para cualquier mejora o sugerencia.

## Contacto

Para cualquier consulta o ayuda adicional, puedes contactar con [Tobias Jara](https://github.com/tobias-tj).
