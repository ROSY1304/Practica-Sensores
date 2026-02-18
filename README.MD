# SensorFlow - Dashboard Reactivo

## Temas Cubiertos

### 1.1 **Definición de Programación Reactiva**
- Uso de `useState` y `useEffect` para manejar flujos de datos.
- La UI es una función del estado: `UI = f(state)`.

### 1.2 **Evolución**
- **Antes:** Manipulación manual del DOM con jQuery (`$('#id').html(...)`).
- **Ahora:** Declarativo con React. El estado cambia → La UI se actualiza sola.

### 1.3 **Web y Móvil**
- **Responsive:** Diseño adaptativo con CSS Grid y Media Queries.
- **Multiplataforma:** Lógica reusable para React Native (mismos hooks, diferentes componentes de vista).

### 1.4 **Frameworks/APIs**
- **Frontend:** React + Vite (rápido, moderno).
- **Backend:** Express.js (API REST minimalista).
- **Comunicación:** Fetch API + JSON.

## Cómo Ejecutar

Para iniciar el proyecto, necesitarás dos terminales abiertas:

```bash
# Terminal 1: Backend (API)
cd server
npm run dev

# Terminal 2: Frontend (React)
cd client
npm run dev