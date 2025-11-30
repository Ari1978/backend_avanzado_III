# Backend Zapatillas 👟  
Proyecto backend desarrollado en Node.js + Express + MongoDB.

Incluye:
- Arquitectura en capas (controllers, services, repositories)
- CRUD de productos, usuarios, carritos y tickets
- DTOs de validación
- Swagger para documentación de APIs
- Logger profesional (Winston + Morgan)
- Autenticación con Passport (sessions)
- Test con Mocha + Supertest
- Imagen Docker lista para ejecutar
- docker-compose.yml para levantar backend + MongoDB

---

## 🐳 Imagen Docker (Docker Hub)

Repositorio de la imagen:  
👉 https://hub.docker.com/r/hagui1978/backend-zapatillas

### Descargar imagen

```bash
docker pull hagui1978/backend-zapatillas:1.0.0


### Ejecutar imagen
```bash
docker run -p 9090:9090 hagui1978/backend-zapatillas:1.0.0


