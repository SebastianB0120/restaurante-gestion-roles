# Sistema de Gestión de Restaurante - Pasta La Vista



Este proyecto es una aplicación web desarrollada en **Django** con una base de datos **SQL Server**. Implementa un sistema completo de gestión para un restaurante, incluyendo el control de acceso basado en roles.



## 🚀 Funcionalidades Implementadas



### 🔐 Control de Acceso por Roles

El sistema maneja tres niveles de acceso:



1.  **Administrador**:
2.  
    *   Control total del sistema.
    *   
    *   Gestión de clientes, empleados, mesas y platos.
    *   
    *   Visualización de todas las órdenes y facturas.
    *   
    *   Acceso al panel de administración de Django.
    *   
2.  **Mesero**:
3.  
    *   Gestión de mesas y platos.
    *   
    *   Registro y actualización de órdenes.
    *   
    *   Consulta de disponibilidad de mesas.
    *   
3.  **Cajero**:
4.  
    *   Gestión de facturación.
    *   
    *   Consulta de órdenes pendientes de pago.
    *   
    *   Registro de pagos y generación de facturas.
    *   


## 🛠️ Tecnologías Utilizadas

*   **Backend**: Django (Python)
*   
*   **Base de Datos**: SQL Server
*   
*   **Frontend**: HTML5, CSS3 (Templates de Django)
*   
*   **Control de Versiones**: Git & GitHub
*   


## 📋 Requisitos de Instalación

1. Clonar el repositorio.
2. 
2. Instalar las dependencias:
3. 
   ```bash
   
   pip install django django-mssql-backend pyodbc
   
   ```
   
3. Configurar la conexión a SQL Server en `config/settings.py`.
4. 
4. Ejecutar las migraciones:
5. 
   ```bash
   
   python manage.py migrate
   
   ```
   
5. Crear un superusuario para el administrador:
6. 
   ```bash
   
   python manage.py createsuperuser
   
   ```
   


## 🗄️ Estructura de la Base de Datos

Se incluye el archivo `database_setup.sql` con el script de creación de tablas corregido para SQL Server.



---

*Actividad actualizada y corregida - Implementación de Roles y Control de Acceso.*
































