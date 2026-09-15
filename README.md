# AlmacenDeColchones
Scripts y estilos CSS personalizados para Tiendanube: Inyección dinámica de etiquetas "Solo Colchón" y optimización de interfaz en celulares.
# Optimizaciones Custom para Tiendanube (Almacén de Colchones)

Este repositorio contiene los códigos personalizados (CSS y JavaScript) aplicados a la tienda para mejorar la experiencia de usuario y evitar reclamos por publicidad engañosa en la venta de colchones sin base.

## 📌 Funcionalidades implementadas

### 1. Etiqueta dinámica "Solo Colchón" (JavaScript)
Un script inteligente que se ejecuta en la página de producto:
- **Detecta:** Lee el título del producto y actúa solo si es un "colchón" suelto (excluyendo sommiers o conjuntos).
- **Crea:** Genera un aviso visual ("Base no incluida").
- **Ubica:** Inserta la etiqueta exactamente en el 4to espacio vacío de la grilla de variantes (a la derecha de "Soporte por persona") para mantener el diseño equilibrado.

### 2. Correcciones de Interfaz / UX (CSS Personalizado)
Reglas de estilo inyectadas en el diseño general de la tienda:
- **Catálogo:** Reemplaza la etiqueta nativa de "Envío Gratis" por el diseño gráfico marrón de Lara exclusivamente en los colchones.
- **Limpieza Móvil:** Oculta permanentemente el código `SKU` debajo del precio.
- **Prevención de Superposición:** Desactiva y oculta el cartel nativo de "¡Última unidad!" en la página del producto para que no tape las fotos en dispositivos móviles.

## 🚀 Cómo instalar o actualizar en Tiendanube

**Para el código JavaScript:**
1. Ir a `Configuración` > `Códigos externos`.
2. Pegar el contenido del archivo `etiqueta-dinamica.js` dentro de la caja de scripts para la tienda.

**Para el código CSS:**
1. Ir a `Mi Tiendanube` > `Diseño` > `Editar diseño` > `CSS personalizado`.
2. Pegar el contenido del archivo `estilos-interfaz.css` al final de la caja de texto.
