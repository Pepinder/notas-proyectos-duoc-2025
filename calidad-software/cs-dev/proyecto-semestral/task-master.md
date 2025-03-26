# Idea final para el proyecto semestral en Técnicas de Calidad de Software

## Taskleton (Gestos de tareas avanzado)

### Requisitos para presentación de proyecto

1. Establece al menos 20 requisitos de software.
2. Crea una tabla para levantar la información.
3. El software presentado incluye un login de acceso y un menú principal.
4. El software presentado incluye al menos un proceso y un reporte o consulta por pantalla.
5. El software presentado es pertinente para su uso a lo largo del semestre.

Con esto entendido, deberemos trabajar con este proyecto, pero primero deberemos desarrollarlo, al momento de desarrollarlo iremos haciendo lo que nos solicitan.

- Este proyecto es sencillo de empezar, pero podemos añadir complejidad (+20 requisitos)
- Tendrá un login, CRUD, procesos y reportes.
- Usaremos tecnologias modernas para el desarrollo de este proyecto, debido a que los sistemas que hay disponibles en Github para probarlos son muy antiguos.

### Características clave

1. Login con JWT (email/contraseña o Google).
2. CRUD de tareas con drag-and-drop.
3. Proceso de colaboración: Compartir tareas con otros usuarios.
4. Reportes: Gráficos de productividad (Chart.js).
5. Extras opcionales: Notificaciones, dark mode, tags.

## STACK TECNOLÓGICO

| Área       | Tecnologías                                                                                               |
| ---------- | --------------------------------------------------------------------------------------------------------- |
| Frontend   | React + Vite (rápido), TypeScript, TailwindCSS (estilos), TanStack Query (datos), Zustand (estado global) |
| Backend    | Node.js + Express o NestJS (más estructura), TypeScript, Prisma (ORM), PostgreSQL/MongoDB                 |
| Auth       | JWT + bcrypt o Firebase Auth                                                                              |
| Despliegue | Front: Vercel, Back: Render (gratis)                                                                      |
