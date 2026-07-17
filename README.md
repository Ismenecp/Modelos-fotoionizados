# Modelos fotoionizados

Documentación y material complementario de la tesis de maestría sobre modelos de fotoionización y discrepancias de abundancias en nebulosas planetarias.

# Material complementario de tesis

Este repositorio reúne los archivos y productos generados durante el desarrollo de la tesis de maestría titulada:

**MODELOS DE FOTOIONIZACIÓN DE NEBULOSAS PLANETARIAS PARA EL ESTUDIO DE LA DISCREPANCIA DE ABUNDANCIAS QUÍMICAS: EFECTO DE GRADIENTES QUÍMICOS**

El trabajo se basa en modelos de fotoionización realizados con **pyCloudy**, utilizados para analizar la estructura física y las discrepancias de abundancias en nebulosas planetarias.

## Contenido del repositorio

Los archivos se encuentran organizados de acuerdo con las distintas familias de modelos consideradas en la tesis.

### Modelos de pyCloudy

Cada familia contiene los archivos correspondientes a los modelos de fotoionización y las gráficas obtenidas a partir de ellos.

Las principales familias de modelos son:

- Modelos de densidad constante.
- Modelos ópticamente delgados.
- Modelos de presión constante.
- Modelos con polvo proporcional al enriquecimiento.

### Familias de modelos

Se tienen cuatro carpetas distintas, correspondientes a cada familia de modelos. Dentro de cada una de ellas se encuentran los archivos de salida generados por pyCloudy.

### Gráficas

Se incluyen las figuras generadas a partir de los resultados de los modelos, entre ellas:

- Temperatura en función del radio.
- Densidad en función del radio.
- Fracciones de ionización de distintos elementos en función del radio.
- Emisividades de distintos elementos en función del radio.

### Perfiles físicos

Esta carpeta contiene los perfiles obtenidos para las diferentes propiedades físicas de los modelos, incluyendo:

- Densidad electrónica.
- Temperatura electrónica.

### Abundancias químicas y ADF

En esta carpeta se encuentran las tablas de los cálculos de abundancias químicas, así como las gráficas de comparación del ADF.

## Organización general

Modelos-fotoionizados/
│
├── densidad_constante/
├── presion_constante/
├── opticamente_delgados/
├── polvo_proporcional/
│
├── graficas/
│   ├── densidad_constante/
│   ├── presion_constante/
│   ├── opticamente_delgados/
│   └── polvo_proporcional/
│
├── perfiles/
│   ├── densidad/
│   │   ├── densidad_constante/
│   │   ├── presion_constante/
│   │   ├── opticamente_delgados/
│   │   └── polvo_proporcional/
│   │
│   └── temperatura/
│       ├── densidad_constante/
│       ├── presion_constante/
│       ├── opticamente_delgados/
│       └── polvo_proporcional/
│
├── mapas_de_lineas/
│   ├── densidad_constante/
│   ├── presion_constante/
│   ├── opticamente_delgados/
│   └── polvo_proporcional/
│
├── adf/
└── abundancias/
