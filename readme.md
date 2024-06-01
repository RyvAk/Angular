# PazYSalvoAppClient

## Instalación y Configuración
1. Instalar Dependencias:
            npm install

2. Crear Proyecto Angular:
            ng new "Nombre del proyecto"

3. Solucionar Errores de Permisos:
Si aparece un error, ejecuta:

            Set-ExecutionPolicy Unrestricted

4. Instalar Angular CLI:
            npm install -g @angular/cli
Esta aplicación fue generada con Angular CLI versión 17.1.0.

# Servidor de Desarrollo
Para iniciar el servidor de desarrollo, ejecuta:
            ng serve

Luego, abre tu navegador y ve a `http://localhost:4200/`. La aplicación se recargará automáticamente cuando modifiques los archivos.

# Estructura del Código
Para crear componentes, usa:
            ng generate component nombre-del-componente

También puedes crear directivas, servicios, clases, guardias, interfaces, enumeraciones y módulos con comandos similares.

# Construcción
Para construir el proyecto, ejecuta:
            ng build

Los archivos construidos se almacenarán en la carpeta `dist/`.

# Pruebas Unitarias
Para ejecutar las pruebas unitarias, usa:
            ng test

# Pruebas End-to-End
Para ejecutar pruebas end-to-end, usa:
            ng e2e

Es posible que necesites instalar un paquete adicional para estas pruebas.

# Instalación de Angular
1. Crear un Nuevo Proyecto:
            ng new PazYSalvoAppClient

2. Crear Directorio de Componentes:
    Crea componentes como `Side-Menu`, `Navbar`, `Login` y `Facturas`.

3. Generar Componentes:
Asegúrate de tener Node y Angular CLI instalados. Luego, genera componentes:
            ng g c components/NombreDelComponente

Ejemplo:
            ng g c components/facturas

4. Instalar Angular Material:
Sigue las instrucciones de Angular Material para la instalación.

# PazYSalvoApp (Backend)

## Características del Backend
*Desarrollado con Swagger en modo Code First.
*Manejo de lógica y datos del backend.
*Documentación automática de la API.
*Implementación de operaciones CRUD y lógica de negocio.
*Integración con el frontend `PazYSalvoAppClient` para el intercambio de datos y funcionalidad completa del sistema.

### Duver Alexander Soto Alzate