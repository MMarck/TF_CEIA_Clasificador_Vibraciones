
<h1 align="center">Clasificador de vibraciones en elementos rotativos</h1>

<p align="center"><img src="archivos estaticos/logo-fiuba.png"/></p> 

![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)
![PyTorch](https://img.shields.io/badge/PytTorch-2.0%2B-orange.svg)
![IMS Dataset](https://img.shields.io/badge/Dataset-IMS-green)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## 🧠 Introducción

Trabajo final de la carrera de especialización en inteligencia artificial (CEIA). Consiste en un modelo para clasificar la señales de vibraciones de maquinaria industrial para determinar si los elementos rodantes presentan una falla. 
## 📋 Tabla de contenidos:


- [Badges o escudos](#badges-o-escudos)
- [Descripción y contexto](#descripción-y-contexto)
- [Guía de usuario](#guía-de-usuario)
- [Guía de instalación](#guía-de-instalación)
- [Cómo contribuir](#cómo-contribuir)
- [Código de conducta](#código-de-conducta)
- [Autor/es](#autores)
- [Información adicional](#información-adicional)
- [Licencia](#licencia)
- [Limitación de responsabilidades - Solo BID](#limitación-de-responsabilidades)

## Descripción y contexto

Este trabajo recopila bibliografía relacionada con el análisis de vibraciones mecánicas junto con implementación de los modelos descriptos en algunos paper. 

## Guía de usuario

Para poder ejecutar los *notebooks* de python se recomienda crear un entorno virtual para evitar conflictos con la librerías instaladas en su sistema operativo. Los *notebooks* están diseñados para ejecutarlos con las opción "Ejecutar Todo". Tomar en consideración que el entrenamiento de algunos modelos puede tener un alto costo computacional.
 	
### 🔧 Instalación y dependencias


```bash
# Paso 1: Clonar el repositorio
git clone https://github.com/MMarck/TF_CEIA_Clasificador_Vibraciones
cd TF_CEIA_Clasificador_Vibraciones

# Paso 2: Crear entorno virtual 
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Paso 3: Instalar dependencias
pip install -r requirements.txt

```
En caso de no tener instalado un extensión para visualizar los *notebooks* de python puede ejecutar el siguiente codigo:
```bash
# Ejecutar en el terminal de VSC 
code --install-extension ms-toolsai.jupyter
```


## Contribuyente/es

- Ing. Marck Murillo (Autor)
- Esp. Carlos Rodríguez (Coordinador)
- Esp. Fabián Sarmiento (Coordinador)
