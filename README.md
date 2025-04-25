# 📁 Analizador de Texto

Aplicación web segura para análisis de archivos de texto con estadísticas detalladas

![Badge](https://img.shields.io/badge/Python-3.8%2B-blue)
![Badge](https://img.shields.io/badge/Flask-2.0%2B-green)

## Características Principales
- 🔒 Validación de MIME types y extensiones
- 📈 Análisis de líneas, palabras y caracteres
- 📅 Registro de fecha de subida
- 📊 Conversión inteligente de tamaños
- 🛡️ Protección HTTPS con Flask-Talisman

## Requisitos Técnicos
- Python 3.8+
- Bibliotecas: `flask`, `python-magic`, `werkzeug`
- Sistema con libmagic (para MIME validation)

## Instalación

1. Clonar repositorio:
```bash
git clone https://github.com/PotOfCode/text_analyzer
```

2. Crear entorno virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```

3. Instalar dependencias:
```bash
pip install flask python-magic-bin werkzeug python-dotenv
```

##Ejemplo de uso

https://text-analyzer-hpij.onrender.com/