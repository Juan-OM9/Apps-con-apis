# 🚀 Colección de Aplicaciones Web con APIs (Flask)

Este repositorio contiene una colección de aplicaciones web desarrolladas en Python utilizando el framework **Flask**. Cada aplicación interactúa con diferentes APIs públicas y servicios externos (como Google Books, TMDB, Firebase, etc.) para mostrar datos en tiempo real.

## 🛠️ Requisitos e Instalación

Para ejecutar cualquiera de estas aplicaciones, necesitas tener Python instalado y configurar un entorno virtual.

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/Juan-OM9/Apps-con-apis.git](https://github.com/Juan-OM9/Apps-con-apis.git)
   cd Apps-con-apis

# 2. Crea y activa tu entorno virtual:

 Bash

python -m venv .venv
   En Windows:
.venv\Scripts\activate

# 3. Instala las dependencias:

  Bash

pip install -r requirements.txt

📱 Aplicaciones Incluidas
A continuación, se detalla cada una de las aplicaciones y su funcionalidad.

📚 1. Buscador de Libros (libros_app.py)
Utiliza la Google Books API para buscar libros, mostrar portadas, autores, descripciones y opciones de compra.

Captura de pantalla:
<img width="1808" height="910" alt="image" src="https://github.com/user-attachments/assets/e8f8789e-34a1-41ce-9de8-693f03e02cfc" />


🎬 2. Buscador de Películas (peliculas_app.py)
Interactúa con la API de TMDB (The Movie Database) para explorar películas populares, ver sinopsis y pósters oficiales.

Captura de pantalla:
<img width="1790" height="912" alt="image" src="https://github.com/user-attachments/assets/aecf1361-2791-44f1-af33-3fa6689fe8d1" />


💬 3. Chat en Tiempo Real (chat_app.py)
Una sala de chat global construida integrando Firebase Realtime Database, permitiendo que varios usuarios interactúen simultáneamente.

Captura de pantalla:
<img width="643" height="616" alt="image" src="https://github.com/user-attachments/assets/0a16e6ab-7250-4f0c-9310-a48e852ce39e" />
<img width="993" height="610" alt="image" src="https://github.com/user-attachments/assets/aeaaa3e9-8d15-43bd-8d56-58d2d01ad870" />


🌦️ 4. Aplicación de Clima (clima_app.py)
Consulta el estado del clima actual en diferentes ciudades utilizando una API meteorológica, mostrando temperatura y condiciones.

Captura de pantalla:
<img width="578" height="850" alt="image" src="https://github.com/user-attachments/assets/91bda4a3-1831-4727-9d86-37671433cde5" />


💱 5. Conversor de Divisas (divisas_app.py)
Obtiene las tasas de cambio en tiempo real para convertir entre diferentes monedas internacionales.

Captura de pantalla:
<img width="586" height="898" alt="image" src="https://github.com/user-attachments/assets/092c8d48-40a3-4475-b464-90993037489c" />


🐙 6. Buscador de Perfiles de GitHub (github_app.py)
Se conecta a la API pública de GitHub para buscar usuarios y mostrar sus repositorios, seguidores y estadísticas básicas.

Captura de pantalla:
<img width="1465" height="894" alt="image" src="https://github.com/user-attachments/assets/1cdf7a66-b674-4165-ae92-14beb9ec6ec4" />


👽 7. Lector de Reddit (reddit_app.py)
Extrae los hilos y publicaciones más populares de Reddit utilizando su API pública.

Captura de pantalla:
<img width="1225" height="905" alt="image" src="https://github.com/user-attachments/assets/46e467fd-85d5-45c2-8110-7691ce1b2244" />


📍 8. Buscador de Lugares (lugares_app.py)
Aplicación para descubrir sitios de interés basada en datos geográficos externos.

Captura de pantalla:
<img width="1461" height="900" alt="image" src="https://github.com/user-attachments/assets/1ee919b6-d1eb-4fbb-8ec5-3b323674a3ba" />


📦 9. API de Productos (productos_api.py)
Una API local (CRUD) que maneja un inventario de productos utilizando una base de datos local (SQLite/Products DB).

Captura de pantalla:
<img width="1821" height="915" alt="image" src="https://github.com/user-attachments/assets/6a1e8f69-77b2-431e-88d2-82c5ba61a17d" />


🏃‍♂️ Cómo ejecutar una aplicación individual
Para iniciar cualquiera de las aplicaciones, asegúrate de estar en la carpeta raíz del proyecto con tu entorno virtual activado y ejecuta:

Bash

python nombre_de_la_app.py
(Ejemplo: python peliculas_app.py)

Luego, abre tu navegador y visita: http://127.0.0.1:5000
