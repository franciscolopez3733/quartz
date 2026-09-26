# Akasa-Puspa — Wiki desplegable con Quartz

Esta bóveda Obsidian es 100% compatible con Quartz v4.

## Despliegue en 3 pasos (GitHub Pages)

1. **Crear repo en GitHub** `akasa-puspa` (público)
2. **Subir esta bóveda:**
   ```bash
   git init
   git add .
   git commit -m "v4 final - 5 novelas + aval Aguilera"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/akasa-puspa.git
   git push -u origin main
   ```
3. **Activar Pages:** Settings > Pages > Source: GitHub Actions

El workflow `.github/workflows/deploy.yml` ya está incluido. Cada push a `main` publicará automáticamente en `https://TU_USUARIO.github.io/akasa-puspa/`

## Configurar URL base

Edita `quartz.config.ts` línea `baseUrl`:
```ts
baseUrl: "franciscolopez3733.github.io/akasa-puspa"
```

## Local

```bash
npm install
npx quartz build --serve
# abre http://localhost:8080
```

## Licencia y aval

- Enciclopedia: CC BY-SA 4.0
- Aval: Ver `00 Inicio/Aval de los autores.md` — mensaje de Juan Miguel Aguilera 26/09/2026: universo abierto para quien quiera escribir sobre él.
