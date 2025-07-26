# Instrucciones para ejecutar la prueba técnica Joonik

## 1. Acceder a la carpeta principal

Abre una terminal y navega a la carpeta donde quieres trabajar. Luego crea y accede a la carpeta principal del proyecto:

```bash
mkdir proyectos
cd proyectos
```

## 2. Clonar los repositorios

Clona los repositorios del backend y frontend:

```bash
git clone https://github.com/stevCount/backend-joonik.git
git clone https://github.com/stevCount/frontend-joonik.git
```

## 3. Copiar configuración inicial

Copia el contenido de la carpeta `configuracion_prueba` dentro de la carpeta `proyectos`.  
Asegúrate de sobrescribir si se te solicita.

## 4. Seguir instrucciones de cada proyecto

- **Backend**: Sigue las instrucciones en el archivo `README.md` ubicado en:

  ```
  proyectos/backend-joonik/README.md
  ```

- **Frontend**: Sigue las instrucciones en el archivo `README.md` ubicado en:

  ```
  proyectos/frontend-joonik/README.md
  ```

## 5. Resultado final

Una vez completados todos los pasos, deberías poder acceder a:

- API Backend: [http://localhost:8080/api/locations](http://localhost:8080/api/locations)
- Frontend: [http://localhost:5173/](http://localhost:5173/)

> **Recomendación:** Usa Postman o cURL para probar el endpoint del backend (requiere API Key).  
> El `README.md` del backend incluye un ejemplo de uso.
