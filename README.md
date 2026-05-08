# TechSupport

Aplicación móvil desarrollada con React Native y MongoDB orientada a la gestión de incidencias y soporte técnico. Permite a los usuarios crear tickets, dar seguimiento a reportes y conectarse con técnicos de soporte de forma sencilla.

## Características principales

- Registro e inicio de sesión de usuarios
- Creación y seguimiento de tickets de soporte
- Asignación de incidencias a técnicos
- Persistencia de datos mediante MongoDB
- Navegación entre pantallas y manejo de estados

## Tecnologías

- React Native
- Node.js
- MongoDB
- Express
- JWT Authentication

## Publicación

Disponible en Google Play Store:

[TechSupport en Play Store](https://play.google.com/store/apps/details?id=com.techsupport)

![Play Store](assets/playstore.png)

## Capturas

![Login](assets/login.png)

![Inicio](assets/dashboard.png)

![Tickets](assets/tickets.png)

![Lista expertos](assets/listExpert.png)

## Instalación y configuración

### Clonar repositorio

```bash
git clone https://github.com/TU_USUARIO/TechSupport.git
cd TechSupport
```

### Instalar dependencias

```bash
npm install
```

o con Yarn:

```bash
yarn install
```

### Variables de entorno

Crear un archivo `.env` en la raíz:

```env
PORT=3000
MONGO_URI=mongodb://localhost:27017/techsupport
JWT_SECRET=tu_secreto_aqui
```

### Ejecutar aplicación Android

```bash
npx react-native run-android
```

## Lo que aprendí

Durante este proyecto aprendí a conectar una aplicación móvil con un backend y una base de datos MongoDB, manejar autenticación mediante JWT y estructurar componentes reutilizables en React Native.
