# Sales_Predictions
Predicción de ventas para productos vendidos en varias tiendas


La data analizada incluye información como:
* Peso del producto
* Si el producto es bajo en grasa o regular
* Categoría a la que el producto pertenece
* Precio máximo de venta al público del producto
* Porcentaje de visibilidad del producto en cada tienda
* El año en que se estableció la tienda
* El tamaño de la tienda
* El tipo de área donde se encuentra la tienda
* Tipo de tienda
* Venta del producto 

**Objetivo**: Definir un modelo de regresión para predecir las ventas

![image](https://user-images.githubusercontent.com/114969058/208265697-49ec3d0a-6436-4a19-854d-a872cd9275f0.png)

 * La categoría con mayor venta es la de frutas y verduras, con un precio promedio de 145$ por producto.  Seguido de la categoría Snacks con un precio de aprox 142$. 
 * La categoría con mayor precio unitario promedio es la de productos de limpieza pal hogar, con una venta de aprox 2 millones, siendo la tercera categoría con mayor demanda.
 * La categoría con el precio unitario promedio mas barato es la de panaderia. 

![image](https://user-images.githubusercontent.com/114969058/208265764-50d75bce-467c-45f9-98a4-ceb0c08323b6.png)

* La variable con mayor correlación con la variable objetivo ( Ventas) es MRP, Precio Máximo de venta al público del producto. 
* La variable peso y año de establecimiento tienen una muy baja correlación con la variable ventas, por tanto no se tendrán en cuenta para los modelos de predicción.

![image](https://user-images.githubusercontent.com/114969058/208265784-1098a7d9-501e-4ed8-8a07-a14c27aa0eeb.png)

De acuerdo a lo anterior, el modelo que mejor se ajusta a las variables para predecir la venta es el árbol de decisión.





