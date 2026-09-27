# Chispa Motos — Distribuidor en línea Yadea

Sitio de venta en línea de motos eléctricas Yadea para México (versión de presentación).

- 36 modelos con existencia real del almacén de Yadea México en Ocoyoacac (inventario del 26 de septiembre de 2026), con foto por color.
- Ficha por modelo, comparador, calculadora de ahorro vs gasolina, estimador de envío y simulador de financiamiento.
- Flujo de apartado en 4 pasos (cobro simulado) y asesor virtual.

## Configuración antes de operar

Al inicio del `<script>` en `index.html`:

- `CONFIG.WHATSAPP`: número de WhatsApp Business (formato 521 + 10 dígitos).
- `CONFIG.DEPOSITO`: monto del apartado.
- `ZONES`: tarifas y tiempos de envío por zona desde Ocoyoacac, Edo. de México.
- `PRODUCTS`: catálogo, precios, existencias por color (`colors: [nombre, muestra, foto, enAlmacén]`) y especificaciones. Los modelos con `price: null` se muestran "a cotizar".

Chispa Motos es un distribuidor independiente. Yadea es marca registrada de Yadea Technology Group Co., Ltd.
