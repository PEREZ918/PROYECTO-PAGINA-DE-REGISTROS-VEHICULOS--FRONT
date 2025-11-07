# PROYECTO-PAGINA-DE-REGISTROS-VEHICULOS--FRONT 

# 🚗 Gestión de Vehículos y Motos — App Web React

En este proyecto implementamos principalmente react.js y javascript para su funcionamiento, este programa nos permitira acceder a la pagina web en la cual se realizan los registros de los vehiculos, en ella veremos todos sus detalles y una imagen descriptiva, ademas de esto la pagina implementa mensajes de alerta en caso de exito o no exito, ademas de esto implementamos bootstrap y SweetAlert2

---

## 🧠 Objetivo del proyecto

El propósito de este proyecto es aplicar los conceptos fundamentales de **React.js**, tales como:
- Componentización y reutilización de código.  
- Manejo de estado con *hooks* (`useState`, `useEffect`, `useRef`, `useImperativeHandle`).  
- Comunicación con APIs REST mediante `fetch`.  
- Integración con Bootstrap y SweetAlert2.  
- Envío de archivos e imágenes mediante `FormData`.  

Además, se busca que los estudiantes experimenten un flujo de desarrollo **profesional** utilizando **buenas prácticas de estructura y modularidad** en proyectos React.

---

## 🧩 Características principales

✅ CRUD completo de **Vehículos** y **Motos**.  
✅ Interfaz amigable basada en **React-Bootstrap**.  
✅ **Modales dinámicos** para agregar y editar registros.  
✅ **Gestión de imágenes** para cada elemento.  
✅ Confirmaciones y alertas con **SweetAlert2**.  
✅ Código organizado en **componentes reutilizables**.  
✅ Conexión a un **backend REST API** (por defecto en `http://localhost:8080/api`).

---

## ⚙️ Tecnologías utilizadas

| Tecnología | Descripción |
|-------------|--------------|
| **React.js (Vite)** | Framework de UI basado en componentes. |
| **Bootstrap 5 / React-Bootstrap** | Estilos y componentes responsivos. |
| **SweetAlert2** | Alertas personalizadas y modales de confirmación. |
| **Fetch API** | Comunicación HTTP con el backend. |
| **JavaScript (ES6+)** | Lógica del cliente. |
| **FormData** | Manejo de formularios y subida de imágenes. |

---

## 📁 Estructura del proyecto

src/
├── components/
│ ├── AlertMessage.js # Manejador centralizado de alertas
│ ├── ItemForm.jsx # Formulario para crear/editar ítems
│ ├── ItemList.jsx # Lista dinámica de ítems (vehículos/motos)
│ └── ItemModal.jsx # Modal que contiene el formulario
│
├── App.jsx # Componente principal con tabs para Vehículos y Motos
├── main.jsx # Punto de entrada de la aplicación
└── index.css # Estilos globales

---

## 🖥️ Vista general

Al ejecutar la aplicación, se muestra una interfaz con **dos pestañas principales**:

- **Vehículos** 🚘  
- **Motos** 🏍️  

Cada pestaña permite:
- Visualizar los registros existentes.  
- Agregar un nuevo elemento mediante un **modal dinámico**.  
- Editar o eliminar registros con **alertas de confirmación**.  

---

## 🔌 Configuración y ejecución

### 1️⃣ Clonar el repositorio

git clone https://github.com/PEREZ918/PROYECTO-PAGINA-DE-REGISTROS-VEHICULOS--FRONT.git
### 2️⃣ Instalar dependencias
npm install

### 3️⃣ Ejecutar la aplicación
npm run dev

### 4️⃣ Configurar el backend
La app se comunica con una API REST disponible en:
http://localhost:8080/api/

## Debes De tener disponibles los siguientes endpoints:
- GET /api/vehiculos
- POST /api/vehiculos
- PUT /api/vehiculos/{id}
- DELETE /api/vehiculos/{id}

- GET /api/motos
- POST /api/motos
- PUT /api/motos/{id}
- DELETE /api/motos/{id}


## PRUEBA DE FUNCIONAMIENTO DE EL FRONT


<img width="1351" height="761" alt="Captura de pantalla 2025-11-06 191121" src="https://github.com/user-attachments/assets/a728349d-1702-423a-ac99-d67bd81b3283" />





Cada registro puede incluir una imagen asociada al vehículo o moto.

### 🧠 Componentes destacados
- ItemList.jsx
Gestiona la visualización de listas y la comunicación con el backend.
Permite editar y eliminar elementos con confirmaciones visuales.
- ItemModal.jsx
Componente reutilizable para abrir un modal con el formulario (ItemForm).
- ItemForm.jsx
Formulario dinámico con validaciones y soporte de imágenes.
- AlertMessage.js
Función centralizada para mostrar alertas usando SweetAlert2.

### 📜 Licencia
Este proyecto se distribuye bajo licencia MIT, por lo que puede ser reutilizado con fines educativos y de aprendizaje, citando su fuente original.

---

## 🔧 Extensiones de VSCode recomendadas

Para un desarrollo óptimo en este proyecto, se recomiendan las siguientes extensiones de Visual Studio Code:

| Extensión | Descripción |
|-----------|-------------|
| **ES7+ React/Redux/React-Native snippets** | Proporciona snippets útiles para React, como `rfc` para crear componentes funcionales. |
| **Prettier - Code formatter** | Formatea automáticamente el código para mantener un estilo consistente. |
| **ESLint** | Herramienta de linting para identificar y corregir problemas en el código JavaScript/React. |
| **Auto Rename Tag** | Renombra automáticamente las etiquetas HTML/JSX de apertura y cierre. |
| **Bracket Pair Colorizer 2** | Colorea los brackets y paréntesis para mejorar la legibilidad del código. |
| **React Extension Pack** | Paquete que incluye varias extensiones útiles para desarrollo en React. |
| **Vite** | Extensión oficial de Vite para soporte en VSCode (si está disponible). |

### FUNCIONAMIENTO APP WEB

## INTERFAZ


<img width="1340" height="628" alt="Captura de pantalla 2025-11-06 141959" src="https://github.com/user-attachments/assets/b40c4a95-d159-4779-99a1-a815d71ec886" />




## MENU DE CREACION, EDICION Y ELIMINACION


<img width="1340" height="619" alt="Captura de pantalla 2025-11-06 142050" src="https://github.com/user-attachments/assets/14417a1c-f6af-45d4-aa26-0ce73c050f0d" />




##  DEMOSTRACION DE VISTA AL YA ESTAR LOS VEHICULOS AGREGADOS


<img width="1347" height="675" alt="Captura de pantalla 2025-11-05 134716" src="https://github.com/user-attachments/assets/8edc030a-d502-4afc-957c-d960c0f1d8b5" />




## DEMOSTRACION DE VISTA AL YA ESTAR LAS MOTOS AGREGADAS


<img width="1354" height="672" alt="Captura de pantalla 2025-11-05 141900" src="https://github.com/user-attachments/assets/90992720-9934-4ed9-b1fd-142826a4680a" />




## MENSAJE DE ALERTA (ERROR AL GUARDAR)


<img width="1358" height="667" alt="Captura de pantalla 2025-11-06 190748" src="https://github.com/user-attachments/assets/055f6fb9-35ff-47f1-8df0-3faf25e96ec3" />





## MENSAJE DE ALERTA (CONFIRMACION DE CAMBIOS)


<img width="1358" height="673" alt="Captura de pantalla 2025-11-06 191504" src="https://github.com/user-attachments/assets/75e18faa-6dff-491d-8df7-9bfaf5a4e90c" />






## MENSAJE DE ALERTA (EXITOSO)


<img width="1352" height="668" alt="Captura de pantalla 2025-11-06 191451" src="https://github.com/user-attachments/assets/5ac88260-a200-4e5f-9514-2157cc8d9dbe" />












