# 🏬 Análisis de negocio basado en comportamiento de cohortes
Este proyecto se centra en el análisis de las campañas de marketing de una tienda virtual, para el cual se realizó una revisión profunda sobre el comportamiento de los usuarios separados por cohorte y la manera en que se distribuyeron las visitas, ventas y margenes de beneficio según los medios de difusión y consumo de los usuarios. Adicionalmente, se aplicaron técnicas de análisis para obtener datos relevantes como lo son LTV, CAC y ROMI

![CAC](https://github.com/justonenicolas/Cohort-based-Business-Analysis/blob/main/CAC.JPG)
![ROMI](https://github.com/justonenicolas/Cohort-based-Business-Analysis/blob/main/ROMI.JPG)
![LTV](https://github.com/justonenicolas/Cohort-based-Business-Analysis/blob/main/LTV.JPG)

## 💡 Habilidades destacadas
* Análisis preparatorio de datos
* Análisis estadístico de datos
* Visualización de datos

## 🔧 Herramientas y librerías utilizadas
* Pandas
* Numpy
* Scipy
* Seaborn
* Matplotlib

## 📊 Conclusiones generales
* Se estima que el promedio de usuarios activos al día es de 907 y que las sesiones activas en promedio son 987, lo cuál implica un nivel de actividad de aproximadamente 1.1 sesiones diarias por usuario
* Se logró evidenciar que el volumen de compras durante los primeros 5 días dentro de la plataforma suele encontrarse por encima de 200, mientras que después de dicho periodo comienzan a disminuir las compras hasta alcanzar niveles inferiores a 100 compras por día a partir del día 10
* A partir del análisis, se obtuvo que la primera cohorte es la que mayor fidelidad ha mostrado a lo largo del tiempo basados en su volumen de ordenes
* Se identificó un promedio de compra por cohorte de $7.29
* Al realizar el cálculo del LTV se identificó que cada usuario aporta un promedio mensual de $37.85
* Al realizar el análisis de costos de distribución se logró identificar que los 4 medios de adquisición que más costos representan, organizados de mayor a menor, son: 3, 4, 5 y 2
* En contraposición, los medios de adquisición más económicos, organizados de mayor a menos, son: 9, 10 y 1. Cabe resaltar que los medios 9 y 10 mostraron comportamientos bastante similares
* Independiente del medio de adquisición, se evidenció una disminución en el ROMI a medida que avanza el tiempo. Este análisis es consistente con la evidencia sobre la disminución de compras promedio a lo largo del tiempo
* Los medios 2 y 3 demuestran tener una rentabilidad bastante similar aunque se encuentran dentro de los tres menos rentables junto con el medio 1
* Los medios más rentables a lo largo del tiempo demuestran ser el 5, 9 y 10, teniendo todos a su vez un comportamiento bastante similar
