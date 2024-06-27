# Dataset-Aves-Reconocimiento-Visual

## Enlace al drive donde se guarda el dataset.
[Dataset en Google Drive](https://drive.google.com/drive/folders/1V7sgAVcGILhxOLi-aKq3kb2_lTILe-g5?usp=drive_link)

## Estructura del dataset
<pre>
├── CSV
│   ├── AGUJA COLINEGRA.csv
│   ├── ALCA COMÚN.csv
│   ├── AVEFRÍA EUROPEA.csv
│   ├── AVIÓN ROQUERO.csv
│   ├── AVOCETA COMÚN.csv
│   ├── CHARRÁN PATINEGRO.csv
│   ├── CHORLITO DORADO EUROPEO.csv
│   ├── ESTORNINO PINTO.csv
│   ├── FLAMENCO COMUN.csv
│   ├── FOCHA COMUN.csv
│   ├── GARCILLA VUEYERA OCCIDENTAL.csv
│   ├── GAVIOTA PATIAMARILLA.csv
│   ├── GAVIOTA REIDORA.csv
│   ├── GOLONDRINA COMUN.csv
│   ├── GORRIÓN COMÚN.csv
│   ├── GRAJILLA OCCIDENTAL.csv
│   ├── JILGUERO EUROPEO.csv
│   ├── MORITO COMÚN.csv
│   ├── PALOMA TORCAZ.csv
│   ├── PARDELA BALEAR.csv
│   ├── PATO CUCHARÓN NORTEÑO.csv
│   ├── SERÍN VERDECILLO.csv
│   └── VENCEJO COMÚN.csv
├── pruebas
│   ├── AGUJA COLINEGRA
│   ├── ALCA COMÚN
│   ├── AVEFRÍA EUROPEA
│   ├── AVIÓN ROQUERO
│   ├── AVOCETA COMÚN
│   ├── CHARRÁN PATINEGRO
│   ├── CHORLITO DORADO EUROPEO
│   ├── ESTORNINO PINTO
│   ├── FLAMENCO COMUN
│   ├── FOCHA COMUN
│   ├── GARCILLA VUEYERA OCCIDENTAL
│   ├── GAVIOTA PATIAMARILLA
│   ├── GAVIOTA REIDORA
│   ├── GOLONDRINA COMUN
│   ├── GORRIÓN COMÚN
│   ├── GRAJILLA OCCIDENTAL
│   ├── JILGUERO EUROPEO
│   ├── MORITO COMÚN
│   ├── PALOMA TORCAZ
│   ├── PARDELA BALEAR
│   ├── PATO CUCHARÓN NORTEÑO
│   ├── SERÍN VERDECILLO
│   └── VENCEJO COMÚN
├── test
│   ├── AGUJA COLINEGRA
│   ├── ALCA COMÚN
│   ├── AVEFRÍA EUROPEA
│   ├── AVIÓN ROQUERO
│   ├── AVOCETA COMÚN
│   └── ...
├── train
│   ├── AGUJA COLINEGRA
│   ├── ALCA COMÚN
│   ├── AVEFRÍA EUROPEA
│   ├── AVIÓN ROQUERO
│   ├── AVOCETA COMÚN
│   └── ...
└── valid
    ├── AGUJA COLINEGRA
    ├── ALCA COMÚN
    ├── AVEFRÍA EUROPEA
    ├── AVIÓN ROQUERO
    ├── AVOCETA COMÚN
    └── ...
</pre>

## Contenido de cada carpeta
- **dataset/**
  - **CSV/**: Scripts y archivos CSV con metadatos que contienen la url de la imágen para descargar mediante los scripts.
  - **pruebas/**: Carpeta con las 23 clases con imágenes adicionales utilizadas para realizar las pruebas, mostrando etiqueta real y predicción.
  - **test/**: Carpeta con las 23 clases con imágenes utilizadas para evaluar el modelo.
  - **train/**: Carpeta con las 23 clases con imágenes utilizadas para entrenar el modelo.
  - **valid/**: Carpeta con las 23 clases con imágenes utilizadas para validar el modelo durante la fase del entrenamiento.
