# Projecte Web amb Docker Compose

Aquest projecte utilitza Nginx, MariaDB i Adminer.

## Requisits
- Tenir Docker i Docker Compose instal·lats.

## Com arrencar el projecte
1. Clona el repositori.
2. Executa:
   docker-compose up -d
3. Accedeix a:
   - Web: http://localhost:8080
   - Gestor BD (Adminer): http://localhost:8081
     - Servidor: base-dades
     - Usuari: root
     - Password: root

## Com aturar-lo
docker-compose down