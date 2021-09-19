#Skatepark

###pg admin settings: 
user: 'postgres',
    password: "1234567",
    host: "localhost",
    port: 5432,
    database: "skatepark"

###pg query: 
CREATE DATABASE skatepark;
CREATE TABLE skaters (id SERIAL, email VARCHAR(50) NOT NULL, nombre
VARCHAR(25) NOT NULL, password VARCHAR(25) NOT NULL, anos_experiencia
INT NOT NULL, especialidad VARCHAR(50) NOT NULL, foto VARCHAR(255) NOT
NULL, estado BOOLEAN NOT NULL);


###install
npm install
node index.js
-> localhost:3000

/index para ver listado
/admin para aprobar usuarios
/datos / login /registro 