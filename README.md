# Fuego de Campo · Carta digital

- `index.html`: la carta para clientes. Arman el pedido y lo mandan por WhatsApp.
- `panel.html`: panel privado para editar la carta (platos, precios, fotos, promos y "abierto hoy").

Los datos están en Supabase (tablas `fdc_*`). La clave que figura en `config.js` es la publicable: la base está protegida con reglas de seguridad (RLS) y solo los usuarios de `fdc_admins` pueden editar.
