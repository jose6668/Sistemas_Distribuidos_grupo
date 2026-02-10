# Sistemas_Distribuídos_grupo

## **Integrantes del proyecto** 

- Vargas Herrera Jose Leonardo 
    - *Rol* 
        - NA
- Buitrago Murcia Jersson Fabián 
    - *Rol* 
        - QA
- Tello Mendez Nicolas
    - *Rol* 
        - NA
- Romero Trujillo Marlon David 
    - *Rol* 
        - NA

### **Presentación de ideas**

- Leonardo 
    - Desarrollar un software de gestión empresarial orientado a una pequeña franquicia compuesta por dos locales (sedes). El sistema estará diseñado para operar de manera concurrente, permitiendo el acceso simultáneo de un número limitado de usuarios por cada sede, garantizando el correcto funcionamiento en tiempo real.<br/>
    El software tendrá como objetivo principal la gestión y control del inventario de cada una de las sedes, asegurando que la información se mantenga actualizada, consistente y diferenciada por local, pero accesible desde un mismo sistema centralizado.

- Jersson
    ### Sistema de Gestión de Flotas (Vehículos)
    El proyecto consiste en crear una plataforma para administrar y supervisar una flota de vehículos, donde sea posible gestionar conductores, registrar unidades y visualizar sus ubicaciones en tiempo real, además de almacenar el historial de recorridos y generar notificaciones ante situaciones como exceso de velocidad o desvíos de ruta. El sistema se implementará mediante una arquitectura distribuida, separando sus funcionalidades en distintos servicios independientes (como autenticación, gestión de vehículos, seguimiento y alertas), cada uno ejecutándose en contenedores Docker. Esta organización permite que el sistema funcione de manera eficiente, soporte múltiples envíos de datos simultáneos y mantenga la información siempre actualizada. El propósito es contar con una aplicación web centralizada que facilite el control y monitoreo de la flota de forma segura y confiable.
    

- Tello
    - La idea del proyecto es desarrollar un sistema para una biblioteca que permita llevar el control de los libros, los lectores y los préstamos de manera organizada. El sistema estará dividido en varias partes, cada una encargada de una función específica, para que pueda funcionar de forma ordenada y permitir que varias personas lo usen al mismo tiempo sin generar conflictos. El objetivo principal es facilitar la administración de la biblioteca, asegurando que la información sobre los libros y los préstamos esté siempre actualizada y pueda consultarse desde un mismo sistema.

- Marlon 
    - Desarrollar un sistema de chat corporativo en tiempo real para una organización con dos sedes, donde varios usuarios puedan comunicarse simultáneamente y recibir mensajes de forma inmediata. El sistema operará con dos servidores para garantizar disponibilidad y soportar más usuarios. Para mantener la conversación sincronizada entre sedes, se usará Redis con Pub/Sub, que permite que cualquier mensaje enviado desde una sede se replique automáticamente en la otra. Así se asegura una comunicación centralizada, rápida y consistente, con posibilidad de crecimiento si se agregan más servidores.

