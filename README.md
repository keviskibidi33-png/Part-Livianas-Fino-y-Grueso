# Particulas Livianas CRM

Microfrontend Vite/React para el formulario de Particulas Livianas consumido por `iframe` desde `crm-geofal`.

## Dominio productivo

- `https://part.livianasfinasgrueso.geofal.com.pe`

## Variables

- `VITE_API_URL=https://api.geofal.com.pe`
- `VITE_CRM_LOGIN_URL=https://crm.geofal.com.pe/login`
- `VITE_MODULE_SLUG=part-livianas`

## Desarrollo

```bash
npm install
npm run dev
```

## Deploy Coolify

El `Dockerfile` ya compila este repo en la raiz `/` con `VITE_MODULE_SLUG=part-livianas`, listo para `https://part.livianasfinasgrueso.geofal.com.pe`.
