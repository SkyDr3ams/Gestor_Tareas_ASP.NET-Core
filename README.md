# Gestor de Tareas - ASP.NET Core 📝

Este repositorio contiene el proyecto desarrollado como seguimiento al webinar **"Uso de ASP.NET Core"**. Es una aplicación web completa basada en el patrón **MVC** que permite a los usuarios gestionar sus tareas personales de forma segura y aislada.

---

## 🚀 Funcionalidades Principales

Este proyecto cumple con todos los requisitos de la evaluación:

* **Autenticación Segura:** Sistema de Registro y Login (Identity) para proteger el acceso.
* **Privacidad de Datos:** Cada usuario tiene su propia lista de tareas. (El Usuario A no puede ver las tareas del Usuario B).
* **CRUD Completo:**
    * ✅ **C**rear tareas nuevas.
    * ✅ **L**eer el listado de tareas.
    * ✅ **A**ctualizar / Editar tareas existentes.
    * ✅ **E**liminar tareas.
* **Filtros y Ordenamiento:** Funcionalidad para filtrar tareas por prioridad o estado.

---

## 🛠 Tecnologías Utilizadas

* **Framework:** ASP.NET Core MVC (.NET 8)
* **ORM:** Entity Framework Core
* **Base de Datos:** SQLite / SQL Server LocalDB
* **Frontend:** Razor Views, Bootstrap

---

## ⚙️ Instrucciones de Instalación y Ejecución

Para ejecutar este proyecto en local, sigue estos pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/SkyDr3ams/Gestor_Tareas_ASP.NET-Core.git](https://github.com/SkyDr3ams/Gestor_Tareas_ASP.NET-Core.git)
    ```

2.  **Abrir el proyecto:**
    Abre el archivo `.sln` con **Visual Studio 2022**.

3.  **Restaurar Base de Datos (IMPORTANTE):**
    Para que el login funcione, debes crear la base de datos localmente.
    * Ve al menú: `Herramientas` > `Administrador de Paquetes NuGet` > `Consola del Administrador de Paquetes`.
    * Ejecuta el siguiente comando:
        ```powershell
        Update-Database
        ```

4.  **Ejecutar:**
    Presiona `F5` o el botón de "Play" para iniciar la aplicación en el navegador.

---

## 👤 Autor

**SkyDreams.**
