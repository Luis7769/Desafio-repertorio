  DATABASE
  
  CREATE DATABASE repertorio ;
  CREATE TABLE canciones (id SERIAL, titulo VARCHAR(50), artistaVARCHAR(50), tono VARCHAR(10));

  Dependecias:
  npm install express
  npm install pg
  node server.js para iniciar servidor

  Consultas:
    POST
  - /cancion
  GET
  - /canciones
  PUT
  - /cancion/:id
  DELETE
  - /cancion/:id
