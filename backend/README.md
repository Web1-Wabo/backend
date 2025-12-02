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

## Reespuesta comando remotos configurarados
gitlab
origin
--o--
gitlab  https://gitlab.com/alvarosanchezsegura40/backend.git (fetch)
gitlab  https://gitlab.com/alvarosanchezsegura40/backend.git (push)
origin  https://github.com/Web1-Wabo/backend.git (fetch)
origin  https://github.com/Web1-Wabo/backend.git (push)

