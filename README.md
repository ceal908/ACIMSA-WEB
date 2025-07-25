
## 🚀 Frontend: Next.js + TypeScript

El cliente está construido en `frontend/` y está listo para ser desplegado en Vercel. Cuenta con:

- Arquitectura modular por features
- Alias para imports (`@components`, `@utils`, etc.)
- ESLint, Prettier y Tailwind configurados
- Archivos base generados automáticamente
- Separación clara entre `app`, `styles`, `config`, etc.

> ✅ **Vercel:** Para desplegar correctamente, asegúrate de que la raíz del proyecto esté configurada como `./frontend`.

## 🛠️ Stack Tecnológico

| Herramienta       | Propósito                              |
|-------------------|----------------------------------------|
| Next.js           | Framework principal de frontend        |
| TypeScript        | Tipado estático y escalabilidad        |
| ESLint + Prettier | Calidad y formato automático del código|
| Tailwind CSS      | Estilos rápidos y personalizables      |
| Git + Scripts     | Control de versiones y automatización  |

## 📦 Instalación local

```bash
cd frontend
npm install
npm run dev