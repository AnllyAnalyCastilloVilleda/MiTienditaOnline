# MiTienditaOnline
## Descripción
¡Bienvenido a **Mi Tiendita Online**! Este es un proyecto de una tienda en línea desarrollado con Node.js y Express, utilizando MSSQL como base de datos.

## Descripción
Este proyecto implementa un backend para gestionar los productos, usuarios y autenticación de una tienda en línea. 

## Tecnologías

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)


### Base de Datos
![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

## Instalación

### Requisitos Previos
Antes de comenzar, asegúrate de tener instalados los siguientes requisitos:
- [Node.js](https://nodejs.org/) (versión 16 o superior)
- [npm](https://www.npmjs.com/) (incluido con Node.js)

### Clonar el Repositorio
Clona este repositorio en tu máquina local:
```bash
git clone https://github.com/AnllyAnalyCastilloVilleda/MiTienditaOnline.git
```

### Instalar Dependencias Necesarias
npm install

## Configuración de la Base de Datos

En el archivo `src/config/db.js`, encontrarás la configuración de la base de datos que necesitas personalizar para tu entorno.

### Modificar los Datos de Conexión

Abre el archivo `src/config/db.js` y cambia los valores en el objeto `connectionSettings` con la información de tu propia base de datos:

```javascript
const connectionSettings = {
  server: "localhost", 
  user: "sa",       
  password: "",         
  database: "GDA00592_OT_AnllyCastillo",  
  port: 1433, 
  options: {
    encrypt: true,
    trustServerCertificate: true, 
  },
};
```
