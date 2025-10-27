# 📊 Tabla de Datos - Plataformas Digitales

Una aplicación web moderna para mostrar y filtrar datos de plataformas digitales con un diseño oscuro minimalista.

## 🚀 Características

- **Filtrado en tiempo real** por país
- **Ordenamiento dinámico** por cualquier columna
- **Interfaz oscura** amigable para los ojos
- **Código JavaScript puro** - sin librerías externas
- **Responsive design** - funciona en móviles y escritorio
- **Backend simplificado** - ideal para desarrolladores junior

## 🛠️ Tecnologías

- **Backend**: Python Flask
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Estilos**: CSS Grid/Flexbox
- **Iconos**: Font Awesome

## 📱 Funcionalidades

### Filtrado
- Filtrar por país usando dropdown
- Resultados instantáneos sin recarga de página

### Ordenamiento
- Click en encabezados de columnas para ordenar
- Iconos visuales muestran dirección de ordenamiento
- Soporte para orden ascendente/descendente
- Ordenamiento inteligente (numérico para usuarios)

### Interfaz
- Tema oscuro minimalista
- Transiciones suaves
- Información en tiempo real de resultados
- Diseño responsive

## 🚀 Instalación y Uso

### Requisitos
```bash
Python 3.7+
Flask
```

### Instalación
```bash
# Clonar el repositorio
git clone https://github.com/Alexander0782/tablas_datos_app.git
cd tablas_datos_app

# Instalar Flask
pip install flask

# Ejecutar la aplicación
python app.py
```

### Acceso
Abrir navegador en: `http://127.0.0.1:5000/tabla`

## 📁 Estructura del Proyecto

```
tablas_datos_app/
├── app.py                 # Aplicación Flask principal
├── static/
│   └── style.css         # Estilos CSS
├── templates/
│   └── tabla.html        # Template HTML principal
└── README.md             # Documentación
```

## 🎨 Diseño

- **Colores**: Tema oscuro (#1a1a1a, #2d2d2d, #333333)
- **Tipografía**: Segoe UI, Tahoma, Geneva, Verdana
- **Iconos**: Font Awesome 6.0
- **Responsive**: Breakpoints en 768px y 480px

## 🔧 Personalización

### Agregar nuevos datos
Modificar el array `datos` en `app.py`:

```python
datos = [
    {"nombre": "Nueva Plataforma", "usuarios": "100M", "fundado": "2023", "pais": "España"},
    # ... más datos
]
```

### Agregar nuevas columnas
1. Agregar campo al array de datos
2. Actualizar HTML en `tabla.html`
3. Modificar función `ordenarDatos()` en JavaScript

### Cambiar colores
Modificar variables CSS en `style.css`:

```css
body {
    background: #tu-color-fondo;
}
```

## 👨‍💻 Para Desarrolladores Junior

Este proyecto está diseñado para ser fácil de entender y modificar:

- **Código comentado** y bien estructurado
- **Funciones separadas** para cada tarea
- **JavaScript vanilla** - sin frameworks complejos
- **Estructura simple** de archivos
- **Documentación completa**

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la [MIT License](LICENSE).

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📊 Datos de Ejemplo

La aplicación incluye datos de prueba de 7 plataformas digitales populares:
- Spotify, Netflix, YouTube, Twitch, TikTok, Instagram, Discord

## 🔗 Enlaces

- [Repositorio en GitHub](https://github.com/Alexander0782/tablas_datos_app)
- [Reportar Issues](https://github.com/Alexander0782/tablas_datos_app/issues)

---

**Desarrollado por Alexander Uribe** - [GitHub](https://github.com/Alexander0782)