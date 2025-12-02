# Backend del Proyecto – FastAPI

## Instalación
pip install -r requirements.txt

## Ejecución
python -m uvicorn main:app --reload

## Endpoints disponibles
- GET /students
- GET /students/{id}

## Testing 
python -m pytest

## Docker
docker build -t daw-backend .
docker run -p 8000:8000 daw-backend

## CI/CD – GitHub Actions
Workflows ubicados en backend/.github/workflows/
- backend-test.yml
- backend-docker.yml

Requiere secrets:
- DOCKERHUB_USERNAME
- DOCKERHUB_TOKEN

## Respuesta de comando introducido
da8a1a0 (HEAD -> rama1_alvaroSanchez, origin/main, origin/HEAD rama2_alvaroSanchez, main) commit 1
## Reespuesta comando remotos configurarados
gitlab
origin
--o--
gitlab  https://gitlab.com/alvarosanchezsegura40/backend.git (fetch)
gitlab  https://gitlab.com/alvarosanchezsegura40/backend.git (push)
origin  https://github.com/Web1-Wabo/backend.git (fetch)
origin  https://github.com/Web1-Wabo/backend.git (push)

