# RickAndMortyGallery
# RickAndMortyGalery

Aplicación desarrollada en Windows Forms (.NET Framework) para explorar los personajes de la serie *Rick and Morty* consumiendo una API REST pública.

---

##  Descripción General

- **Nombre:** RickAndMortyGalery  
- **Objetivo:** Mostrar información visual y detallada de personajes de *Rick and Morty*.  
- **Funcionalidades:**
  - Carga de personajes desde API.
  - Visualización en tabla o galería con imágenes.
  - Detalles del personaje (origen, dimensión, especie, estado).
  - Enlaces a la API y plataformas donde ver la serie (HBO, Prime Video).

---

##  Tecnologías Utilizadas

- Lenguaje: **C#**
- Interfaz: **Windows Forms (.NET Framework 4.7.2)**
- IDE: **Visual Studio 2022**
- API REST: [https://rickandmortyapi.com](https://rickandmortyapi.com)
- Deserialización: **System.Text.Json**

---

## Arquitectura y Diseño

- **Form1.cs:** Carga la lista de personajes y los muestra.
- **DetallePersonaje.cs:** Muestra información detallada del personaje seleccionado.
- **Modelos:**  
  - `Personaje`: datos generales del personaje.  
  - `Origen`: datos básicos del origen.  
  - `OrigenDetalle`: información ampliada del origen (dimensión, residentes...).

---

##  Instalación y Uso

### Requisitos:
- Windows 10 o superior
- Visual Studio 2022
- .NET Framework 4.7.2+

### Ejecución:
1. Clonar o descargar el repositorio.
2. Abrir la solución con Visual Studio.
3. Compilar (`Ctrl + Shift + B`) y ejecutar (`Ctrl + F5`).
4. Pulsar **"Cargar personajes"** para empezar.

---

##  Enlaces útiles

- API oficial: [https://rickandmortyapi.com](https://rickandmortyapi.com)
- Ver la serie:
  - [HBO](https://www.hbo.com/rick-and-morty)
  - [Prime Video](https://www.primevideo.com/detail/0P59D3OVCDE7AZJ9SGXT8X6A03)

---

## Créditos

Aplicación desarrollada con fines académicos para prácticas de consumo de APIs REST con C#.

