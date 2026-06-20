# qr_monitoreo

Sitio para mostrar archivos y contenido de RONAP a través de un QR.

## 🚀 Stack

- **Astro** — Framework web
- **TypeScript** — Tipado estático
- **Tailwind CSS v4** — Estilos utilitarios
- **Supabase** — Backend (PostgreSQL + Storage + Auth)

## 🧞 Comandos

| Comando             | Acción                                |
| :------------------ | :------------------------------------ |
| `pnpm install`      | Instalar dependencias                 |
| `pnpm dev`          | Iniciar servidor de desarrollo        |
| `pnpm build`        | Compilar para producción              |
| `pnpm preview`      | Previsualizar build local             |

## 🔐 Seguridad

Este proyecto utiliza **Supabase Auth** para autenticación y **Row Level Security (RLS)** para proteger los datos.  
Ejecuta `supabase-rls.sql` en el SQL Editor de Supabase para habilitar las políticas de seguridad.

## 📁 Variables de Entorno

Copia `.env.example` a `.env` y completa las credenciales de Supabase:

```
PUBLIC_SUPABASE_URL=https://tu-proyecto.supabase.co
PUBLIC_SUPABASE_ANON_KEY=tu-anon-key
```
