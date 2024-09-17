Esta base de datos está diseñada para gestionar eficientemente el inventario de propiedades y los agentes inmobiliarios que las gestionan. Se compone de dos tablas principales:

Tabla de Propiedades: Esta tabla almacena información detallada de las propiedades disponibles para la venta o alquiler. Incluye campos como la dirección, ciudad, tipo de propiedad (casa, departamento, etc.), precio, tamaño y una descripción. Cada propiedad está vinculada a un agente responsable de su gestión.

Tabla de Agentes: Esta tabla contiene la información personal y de contacto de los agentes inmobiliarios, como su nombre, teléfono, correo electrónico, y número de licencia. Cada agente puede gestionar varias propiedades.

La relación entre estas dos tablas está definida por el campo id_agente, que conecta a los agentes con las propiedades que gestionan. Esta estructura permite mantener un control organizado sobre las propiedades disponibles y los agentes asignados a cada una de ellas, garantizando una gestión eficiente de los bienes inmuebles.