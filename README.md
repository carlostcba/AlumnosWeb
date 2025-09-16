**Editar el archivo `.env`** con tus credenciales:
```env
# Configuracion del servidor
PORT=3000
NODE_ENV=development

# Configuracion de base de datos SQL Server
DB_SERVER=db_ip_server
DB_NAME=db_name
DB_USER=db_user
DB_PASSWORD=db_pass

# Autenticacion Google OAuth 2.0
GOOGLE_CLIENT_ID=XXXXXXXXXXXXXXXXXXX.googleusercontent.com
GOOGLE_CLIENT_SECRET=GOCSPX-XXXXXXXXXXXXXXXXXXX
GOOGLE_CALLBACK_URL=https://tudominio.com/auth/google/callback
GOOGLE_WORKSPACE_DOMAINS=tudominio.com,tudominio.com.ar

# Seguridad de sesiones
SESSION_SECRET=genera_una_clave_aleatoria_de_64_caracteres_aqui
SESSION_NAME=lasalle_session
SESSION_MAX_AGE=86400000
SESSION_SECURE=false

# Configuracion de proxy
TRUST_PROXY=false

# Configuracion de CORS (opcional)
ALLOWED_ORIGINS=*
```
