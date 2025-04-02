

Las dos tablas van a ir unidas por el id pieza e id proveedor.


Tabla PIEZAS: (tienda ciclismo)
-Ruedas
-Manillar
-Sillín
-Suspensión
-Casco
-Guantes
-Maillot
-Zapatillas
-Gafas
-Luces


           (categorias) ¿habría que asignarlas por ID?
  RECAMBIO       |     ROPA       | SEGURIDAD
================================================
 Ruedas          |  Guantes       |  Casco
 Manillar        |  Maillot       |  Gafas
 Sillín          |  Zapatillas    |  Luces
 Suspensión




 Proveedor 1  |   Proveedor 2    |  Proveedor 3   |  Proveedor 4   |  Proveedor 5   |  Proveedor 6
 ===================================================================================================
 Casco        |   Guantes        |   Luces        |   Guantes      |   Ruedas       |   Casco
 Gafas        |   Maillot        |   Ruedas       |   Maillot      |   Manillar     |   Gafas
 Luces        |   Zapatillas     |   Manillar     |   Zapatillas   |   Sillín       |   Luces
 Guantes      |   Casco          |   Sillín       |                |   Suspensión   |
              |   Gafas          |   Suspensión



El ID estará formado por 5 caracteres + números