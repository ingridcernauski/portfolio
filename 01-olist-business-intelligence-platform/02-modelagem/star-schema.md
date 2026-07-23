# Modelagem Star Schema

## Tabela Fato

### Fato_Vendas

Origem:

- olist_order_items_dataset.csv

Granularidade:

Uma linha representa um item vendido em um pedido.

---

## Dimensões

### Dim_Cliente

Origem:

olist_customers_dataset.csv

Chave:

customer_id

---

### Dim_Produto

Origem:

olist_products_dataset.csv

Chave:

product_id

---

### Dim_Vendedor

Origem:

olist_sellers_dataset.csv

Chave:

seller_id

---

### Dim_Calendario

Será criada no Power BI.

---

### Dim_Pagamento

Origem:

olist_order_payments_dataset.csv
