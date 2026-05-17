# Sistema de Gestión de Inventario

Sistema de gestión de inventario desarrollado en Java utilizando JavaFX, Maven y MySQL.  
El proyecto implementa arquitectura MVC, patrón DAO y una interfaz moderna en modo oscuro para mejorar la experiencia de usuario.

---

# Características Principales

- Inicio de sesión de usuarios
- Gestión de productos
- Gestión de transacciones
- Navegación moderna con JavaFX
- Arquitectura MVC
- Implementación del patrón DAO
- Integración con MySQL
- Interfaz moderna en Dark Mode
- Pruebas unitarias con JUnit
- Organización modular del proyecto

---

# Tecnologías Utilizadas

| Tecnología | Descripción |
|---|---|
| Java | Lenguaje principal del proyecto |
| JavaFX | Interfaz gráfica moderna |
| Maven | Gestión de dependencias |
| MySQL | Base de datos relacional |
| JDBC | Conexión con base de datos |
| ORMLite | Implementación ORM |
| DAO Pattern | Acceso desacoplado a datos |
| JUnit 5 | Pruebas unitarias |
| FXML | Diseño de vistas |
| CSS JavaFX | Personalización visual |

---

# Arquitectura del Proyecto

El proyecto sigue una arquitectura MVC (Model - View - Controller).

## Modelos
Contienen la estructura y lógica de datos:
- Product
- Transaction
- User
- Manufacturer
- Customer

## Vistas
Construidas con JavaFX y FXML:
- Login.fxml
- Home.fxml
- Products.fxml
- Transactions.fxml

## Controladores
Gestionan la lógica de interacción:
- LoginController
- HomeController
- ProductsViewController
- TransactionsController

## Servicios
Manejo de autenticación, base de datos y utilidades:
- DBConnection
- Authenticator
- Authorizer
- DBHandler

## DAO
Implementación del patrón DAO:
- ProductDAO

---

# Mejoras Implementadas

## Interfaz de Usuario
- Conversión completa a JavaFX
- Implementación de diseño Dark Mode
- Sidebar moderno de navegación
- Traducción completa al español
- Mejor organización visual

## Navegación
- Navegación entre vistas mediante controladores
- Sidebar interactivo
- Mejora en experiencia de usuario

## Base de Datos
- Integración con MySQL
- Uso de ORMLite
- Separación de lógica mediante DAO

## Seguridad
- Validación de usuarios
- Control de acceso
- Autenticación de sesión

## Código
- Organización modular
- Separación por paquetes
- Eliminación de código legado
- Mejor mantenimiento y escalabilidad

---

# Estructura del Proyecto

```text
src
├── main
│   ├── java
│   │   └── inventory
│   │       ├── controllers
│   │       ├── dao
│   │       ├── models
│   │       ├── services
│   │       └── views
│   └── resources
│       └── gui_images
└── test