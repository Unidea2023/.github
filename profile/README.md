<div align="center">

# 🍊 Estudis

</div>

![](/profile/Final.png)

- [Apuntes](/profile/Apuntes.md)


---

### Historias de Usuario (Metodologias Agiles)

## Iniciar Sesion
**ID:** Iniciar Sesion

**TÍTULO:** Como usuario quiero iniciar sesion para poder subir compartir mis archivos

**REGLAS DE NEGOCIO:** 
- mail no registrado
- Contraseña con mas de 6 caracteres

**CRITERIOS DE ACEPTACIÓN:** 

#### **Escenario 1:** Escenario exitoso

`Dado` que el usuario Juan no esta registrado, y la contraseña juan123 no tiene mas de 6 caracteres

`Cuando` el usuario ingresa Juan, juan123

`Entonces` El sistema inicia sesión y habilita las opciones para mirar, subir y descargar archivos

#### **Escenario 2:** Escenario fallido por usuario ya registrado

`Dado` que el usuario Juan no esta registrado, y la contraseña juan123 no tiene mas de 6 caracteres

`Cuando` el usuario ingresa Juan, juan123

`Entonces` El sistema inicia sesión y habilita las opciones para mirar, subir y descargar archivos

#### **Escenario 3:** Escenario fallido por contraseña incorrecta

`Dado` que el usuario Juan no esta registrado, y la contraseña juan123 no tiene mas de 6 caracteres

`Cuando` el usuario ingresa Juan, juan123

`Entonces` El sistema inicia sesión y habilita las opciones para mirar, subir y descargar archivos

---

## Cerrar Sesion
**ID:** Cerrar Sesion

**TÍTULO:** como usuario quiero cerrar sesión para proteger mis datos personales

**REGLAS DE NEGOCIO:** 

**CRITERIOS DE ACEPTACIÓN:** 

#### **Escenario 1:** título del criterio.
`Dado` que el usuari Juan tiene una sesión abierta

`Cuando` el usuario presiona el boton "cerrar sesion"

`Entonces` El sistema cierra la sesion y deshabilita las opciones para mirar, subir y descargar archivos

---

## Descargar Archivo
**ID:** Descargar Archivo

**TÍTULO:** Como usuario quiero descargar el archivo para poder usarlo

**REGLAS DE NEGOCIO:** 
- Si el usuario tiene mas de 3 archivos descargados en el dia, se muestra en pantalla "Para seguir descargando suscribete"

**CRITERIOS DE ACEPTACIÓN:** 

#### **Escenario 1:** Descarga Exitosa
`Dado` que el usuario Manuel tiene 1 archivos descargados en el dia que es menor al maximo de 3 archivos y tiene los datos de una tarjeta valida

`Cuando` el usuario presiona el boton "Descargar Archivo" e ingresa los datos de una tarjeta valida

`Entonces` El sistema descarga el archivo y aumenta en 1 la cantidad de descargas del usuario

#### **Escenario 2:** Descarga fallida por falta de intentos
`Dado` que el usuario Lionel tiene 3 archivos descargados en el dia que es igual al maximo de 3 archivos y tiene los datos de una tarjeta valida

`Cuando` el usuario presiona el boton "Descargar Archivo" e ingresa los datos de una tarjeta valida

`Entonces` El sistema muestra en pantalla "Para seguir descargando suscribete"

#### **Escenario 3:** Descarga fallida por problemas con la tarjeta
`Dado` que el usuario Diego tiene 2 archivos descargados en el dia que es menor al maximo de 3 archivos y tiene los datos de una tarjeta invalida

`Cuando` el usuario presiona el boton "Descargar Archivo" e ingresa los datos de una tarjeta invalida

`Entonces` El sistema informa que hay problemas con la tarjeta

---


