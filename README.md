# Challenge-Alura-Store

En este challenge se aplica lo aprendido del curso de Alura Latam en el cual se nos dio una problemática donde se tenía a un señor de nombre Juan el cual tiene 4 tiendas y busaca vender una de ellas para esto se pide realizar un análisis con el objetivo de que se tenga el mejor resultado para ofrecer la solución más objetiva y que se tengan las mejores ganancias.

Para la realización de este challenge utilizamos la librería de pandas con las cuales realizamos todas las operaciones y la librería de matplotlib la cual nos permitió realizar gráficos.
El análisis consta de 5 puntos los cuales son: 
* Análisis de facturación por tienda
* Ventas por categoría
* Calificación promedio de la tienda
* Productos más y menos vendidos
* Envió promedio de tienda

Para el primer punto utilizamos el siguiente código: 
´´´ 
facturacionTienda1 = tienda['Precio'].astype(float).sum()
facturacionTienda2 = tienda2['Precio'].astype(float).sum()
facturacionTienda3 = tienda3['Precio'].astype(float).sum()
facturacionTienda4 = tienda4['Precio'].astype(float).sum()


print(f"Facturación Tienda 1: ${facturacionTienda1:.2f}")
print(f"Facturación Tienda 2: ${facturacionTienda2:.2f}")
print(f"Facturación Tienda 3: ${facturacionTienda3:.2f}")
print(f"Facturación Tienda 4: ${facturacionTienda4:.2f}")
´´´
