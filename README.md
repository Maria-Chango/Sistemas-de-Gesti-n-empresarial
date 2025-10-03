# Sistemas-de-Gestion-empresarial
# 🎸 Sistema de Gestión de Inventario - GuitarStock Manager

## 📌 Descripción
GuitarStock Manager es un sistema de gestión de inventario desarrollado en **Go** con el framework **Gin Gonic** y el ORM **GORM**.  
Está diseñado para una tienda de guitarras eléctricas, con el objetivo de optimizar el control de productos, proveedores y movimientos de stock mediante un backend seguro y escalable.

-----------------

## 🎯 Objetivos
- Registro y control automatizado de entradas y salidas de inventario.
- Monitoreo en tiempo real de niveles de stock.
- Alertas preventivas cuando un producto alcanza su nivel mínimo.
- Generación de reportes confiables en formatos **JSON/CSV**.
- Acceso seguro mediante autenticación JWT y roles de usuario.

----------------

## ⚙️ Funcionalidades Principales
- **Gestión de productos**: CRUD de guitarras, accesorios y equipos.
- **Movimientos de inventario**: registro de entradas (compras) y salidas (ventas).
- **Control de stock mínimo**: alertas automáticas de reposición.
- **Gestión de proveedores**: CRUD de proveedores y contactos.
- **Reportes**: exportación de estadísticas en JSON/CSV.
- **Autenticación y roles**:
  - **Admin** → control total.
  - **Vendedor** → registro de movimientos y consulta.
  - **Consulta** → acceso de solo lectura.

---------------------

## 🛠️ Tecnologías
- **Lenguaje:** Go (Golang)  
- **Framework API:** Gin Gonic  
- **ORM:** GORM  
- **Base de Datos:** MySQL (o PostgreSQL)  
- **Seguridad:** JWT + bcrypt  
- **Gestión de entorno:** godotenv  


## 📂 Estructura del Repositorio
