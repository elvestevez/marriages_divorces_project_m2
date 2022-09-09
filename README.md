# Análisis demográfico matrimonios y divorcios

Estudio del estado civil de la población española y de los fenómenos demogŕáficos que impactan en el cambio de estado civil: 

- Matrimonios.
- Divorcios, separaciones y nulidades.

Se ha realizado un análisis de la población en su conjunto a nivel nacional, sin distinguir por provincia, edades, ocupación u otras características que puedan concretar situaciones más específicas de la población.

Se ha incluido la condición de género para observar el comportamiento en función del sexo de la población. 

En 2005 se aprobó la ley que permite en España el matrimonio entre personas del mismo sexo. Se incorpora en el análisis el impacto del género en estos fenómenos demográficos (matrimonios, separaciones).

---

### **Origen de los datos**

Los datos origen se han extraido del portal del Instituto Nacional de Estadística (INE).

Por un lado, se ha consultado la población anual según género y estado civil desde el año 2005. Se considera la población a partir de 16 años, ya que es la edad legal en España para contraer matrimonio y, por tanto, población para la que aplica el cambio de estado civil.

Por otro lado, se consulta el número de matrimonios anual ocurridos desde 2005 hasta 2021. Se distingue si el matrimonio ocurre entre personas de distinto sexo. En el caso de mismo sexo, se identifica si es entre hombres o mujeres.

Se consulta, también, el número anual de divorcios, separaciones y nulidades. En este caso desde 2013, al no haber encontrado información anterior, y hasta el último año publicado, 2021.

No se tienen en cuenta otros tipos de uniones y separaciones como pareja de hecho.

---

### **Tecnologías**
Python, Pandas, PowerBI (PBI).

---
### **Proceso**

Para la elaboración del proyecto se han llevado a cabo los siguientes pasos:

1. Extracción.

    Consulta de los datos en la fuente origen, [INE](https://www.ine.es/).

2. Limpieza y organización de los datos.

    Se trabaja en python con la librería pandas la limpieza, filtrado, combinación y distintas operaciones con los datasets originales.

    Se generan nuevos datasets con los datos organizados para realizar el análisis e informe en la herramienta PBI.

    Disponibles los datasets originales y finales y los notebooks de trabajo en las carpetas data y notebooks, respectivamente.

3. Informe.

    Se genera un report de PBI con el análisis de los datos con el objetivo de poder obtener conclusiones para distintos usos como pueden ser de ámbito político, social o económico.

---

### **Estructura del proyecto**

```
└── project
    ├── .gitignore
    ├── README.md
    └── data
        └── INE    
        └── PBI
    └── notebooks    
    └── reports 
```