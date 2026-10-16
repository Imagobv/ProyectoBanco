# ProyectoBanco

Sistema web de gestión bancaria y simulador de operaciones financieras desarrollado con TypeScript (Angular y Node.js). El proyecto incluye autenticación de usuarios, persistencia en MySQL y despliegue en servidor Linux (AWS EC2).

## Características Principales

* Autenticación y Seguridad: Inicio de sesión protegido con Angular Guards para el manejo de rutas y control de acceso.
* Gestión de Cuentas y Tarjetas: Alta y administración de cuentas bancarias y tarjetas asociadas.
* Transacciones: Módulo de transferencias entre cuentas con actualización de saldo y registro en tiempo real.
* Historial de Movimientos: Consulta detallada de entradas y salidas de dinero.
* Simulador de Créditos: Herramienta para el cálculo y proyección de préstamos.

## Tecnologías Utilizadas

* Frontend: Angular, TypeScript, HTML5, CSS3, Componentes UI (Angular Material / PrimeNG)
* Backend: Node.js / Express, TypeScript / JavaScript
* Base de Datos: MySQL
* Infraestructura y Cloud: AWS EC2, Linux (Ubuntu Server)
* Herramientas: Git, Postman

## Configuración e Instalación Local

### Requisitos previos
* Node.js (v18 o superior)
* MySQL Server
* Angular CLI (`npm install -g @angular/cli`)

### Pasos para ejecutar

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/Imagobv/ProyectoBanco.git](https://github.com/Imagobv/ProyectoBanco.git)
   cd ProyectoBanco
