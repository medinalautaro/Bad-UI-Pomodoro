"Necesito un openapi.yaml (3.1) para una API de comparación de precios de productos online 

 recursos:
 Product {id, name, sku?, current_price, currency, cost?, min_margin?}
 Competitor {id, name, product_url, marketplace, product_id}
 Price {id, amount, currency, source, competitor_id?, product_id, checked_at} 
 
 endpoints:
 GET /products POST /products GET /products/{id}/competitors 
 POST /products/{id}/competitors -> 201 / 400 / 404
 GET /products/{id}/prices 
 POST /products/{id}/price-checks -> 202 / 400 / 404 
 DELETE /products/{id}/competitors/{competitorId}recursos:"

Excepto con el 'recursos:' del final, este prompt estuvo y funciono muy bien, me dio directamente definidos type, required y format.

"Agrégame: 

 recursos: 
 Webs {id, nombre, url, precioScrap} 
 
 endpoints: 
 GET /webs 
 POST /webs -> 202 / 400 / 404 
 DELETE /webs/{id}/"

Use el mismo formato para agregar los nuevos endpoint, funciono muy bien. Estrategia exitosa en solo 2 prompts 