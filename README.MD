# Paso 1: Construir una imagen en Docker
`docker build -t hola-mundo-app:1.0 .`

# Paso 2: Aplicar los archivos en Kubernetes
### 1. Aplica el despliegue
`kubectl apply -f deployment.yaml`

### 2. Aplica el servicio
`kubectl apply -f service.yaml`

# Paso 2: Acceder a la aplicación
### Obtener la IP del servicio
`kubectl get service hola-mundo-service`   

