# SkyTab POS Landing Page

Landing page moderna y mobile-friendly para SkyTab POS.

## 🚀 Características

- ✅ Diseño 100% responsive (mobile-first)
- ✅ Animaciones suaves
- ✅ Formulario funcional que envía a email
- ✅ Optimizado para conversión
- ✅ Secciones: Hero, Beneficios, Características, Testimonial, Precio, Contacto

## 📦 Deploy Rápido

### Opción 1: Vercel (Recomendado)

1. Crea cuenta en [vercel.com](https://vercel.com)
2. Instala CLI: `npm i -g vercel`
3. En esta carpeta: `vercel`
4. Sigue las instrucciones (login + deploy)

**O arrastra esta carpeta directamente en vercel.com → "New Project" → "Upload"**

### Opción 2: Netlify

1. Crea cuenta en [netlify.com](https://netlify.com)
2. Arrastra la carpeta `skytab-landing` a netlify.com
3. Listo

### Opción 3: Cloudflare Pages

1. Crea cuenta en [cloudflare.com](https://cloudflare.com)
2. Pages → "Upload assets"
3. Sube todos los archivos

## 📧 Configurar Formulario de Contacto

El formulario usa **Web3Forms** (servicio gratuito):

1. Ve a [web3forms.com](https://web3forms.com)
2. Registra tu email: **Saules86@gmail.com**
3. Recibirás un `access_key`
4. Edita `index.html` línea 362:
   ```javascript
   access_key: "TU_KEY_AQUI"
   ```

**Alternativa más directa:** Usa el servicio [Formspree](https://formspree.io):
- Crea cuenta con Saules86@gmail.com
- Crea un form
- Reemplaza la URL del fetch por la que te dé Formspree

## 🎨 Personalización

Todo está en un solo archivo HTML para facilitar edición:

- **Colores:** Línea 10-16 (Tailwind config)
- **Textos:** Busca las secciones y edita directamente
- **Logo:** Línea 26 (actualmente texto "SkyTab")
- **Imágenes:** Actualmente usa emojis, puedes reemplazar con `<img>` tags

## 📱 Mobile Friendly

- Menú hamburguesa en móvil
- Grid responsivo (1 col móvil → 2-3 col desktop)
- Botones y formularios optimizados para touch
- Texto escalable según tamaño pantalla

## 🔧 Próximos Pasos

1. Deploy en Vercel/Netlify
2. Configura Web3Forms con tu email
3. Compra dominio en Cloudflare
4. Conecta dominio a tu deploy
5. ¡Listo para recibir leads!

---

**Stack:** HTML + Tailwind CSS CDN + Vanilla JS
**Deploy:** Vercel/Netlify/Cloudflare Pages
**Email:** Web3Forms (gratis hasta 250/mes)
