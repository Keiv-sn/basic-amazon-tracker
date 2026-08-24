# Amazon Global Price Tracker

<p align="center">

  <img src="assets/demo.gif" alt="Demo del Amazon Global Price Tracker" width="900">

</p>

Aplicación web para consultar y realizar seguimiento de precios de productos de Amazon, mostrando el historial de precios y enlaces directos a los productos.

> Proyecto funcional — desarrollado como una herramienta de seguimiento de precios utilizando scraping y visualización de datos.

---

## Funcionalidades

* **Consulta de productos** — obtiene información y precio de productos de Amazon
* **Seguimiento de precios** — permite trackear productos seleccionados
* **Historial de precios** — registra y muestra la evolución del precio
* **Visualización** — genera gráficos simples para analizar los cambios de precio
* **Enlace al producto** — proporciona el enlace directo al producto de Amazon

---

## Stack

| Tecnología    | Uso                                |
| ------------- | ---------------------------------- |
| Python        | Lenguaje principal                 |
| BeautifulSoup | Web scraping y extracción de datos |
| Streamlit     | Interfaz web                       |
| Pandas        | Procesamiento y manejo de datos    |

---

## Arquitectura

El proyecto mantiene una estructura sencilla orientada a la consulta, procesamiento y visualización de datos:

```text
amazon-global-price-tracker/
├── app.py              # Aplicación principal
├── requirements.txt    # Dependencias
├── assets/             # Recursos visuales
└── README.md
```

---

## Instalación

**Requisitos:** Python 3.11 o superior

```bash
# 1. Clonar el repositorio

git clone https://github.com/Keiv-sn/amazon-global-price-tracker.git

cd amazon-global-price-tracker

# 2. Crear entorno virtual (recomendado)

python -m venv env

source env/bin/activate        # Linux / Mac
env\Scripts\activate           # Windows

# 3. Instalar dependencias

pip install -r requirements.txt
```

---

## Uso

Ejecutar la aplicación con Streamlit:

```bash
streamlit run app.py
```

La aplicación se abrirá automáticamente en el navegador.

---

## Estado del proyecto

* [x] Consulta de productos de Amazon
* [x] Obtención de precios
* [x] Obtención de enlaces
* [x] Seguimiento de productos
* [x] Visualización mediante gráficos
* [ ] Mejoras en el sistema de seguimiento
* [ ] Nuevas funcionalidades de análisis

---

## Autor

Desarrollado por **[Keiv]**

---

## Licencia

MIT License — libre para usar, modificar y distribuir.
