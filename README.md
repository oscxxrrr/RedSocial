<!-- ====================== BANNER ====================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:09090B,50:18181B,100:3F3F46&height=200&section=header&text=Red%20Social%20PHP&fontSize=42&fontColor=ffffff&fontAlignY=40&desc=Desarrollo%20Web%20con%20Antigravity%20UI&descAlignY=65&descAlign=50&animation=fadeIn" alt="Banner"/>
</p>

---

## 📌 Sobre el Repositorio

Este repositorio contiene el desarrollo de una **Red Social full-stack** construida desde cero como parte de los proyectos prácticos de desarrollo web. 

El sistema implementa un backend robusto en **PHP**, persistencia de datos relacional con **MySQL**, y una interfaz de usuario minimalista y moderna adaptada al concepto visual **Antigravity**, combinando estilos limpios en **CSS3** y **HTML5**.

---

## 🛠️ Tecnologías y Herramientas

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📂 Contenido y Módulos

El proyecto se divide en módulos lógicos para asegurar la escalabilidad y el mantenimiento del código:

- **Autenticación y Sesiones:** Registro de usuarios, inicio de sesión seguro mediante `password_hash()` y gestión de sesiones activas.


- **Muro de Publicaciones (Feed):** Creación, lectura y eliminación de posts de texto e imágenes con diseño inspirado en la estética *Antigravity*.


- **Sistema de Interacciones:** Funcionalidad de *likes* y comentarios asociados a cada publicación.


- **Perfil de Usuario:** Panel personalizable con biografía, estadísticas de publicaciones y gestión de datos de cuenta.

---

## 🚀 Cómo ejecutar el proyecto localmente

Para poner en marcha y probar la red social rápidamente en tu equipo, sigue estos pasos:

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/oscxxrrr/CURSO-DWEC-20262_027.git
   ```

2. **Abre el proyecto en tu editor de código** (como Visual Studio Code) y sitúate en la carpeta raíz del proyecto desde la terminal integrada.

3. **Inicia el servidor local de PHP** ejecutando el siguiente comando:

   ```bash
   php -S localhost:80
   ```
   *(Nota: Si el puerto 80 requiere permisos de administrador en tu sistema operativo, puedes usar alternativamente `php -S localhost:8000`)*.

4. **Abre tu navegador** y entra en `http://localhost` (o `http://localhost:8000` si usaste otro puerto) para ver la aplicación funcionando.
