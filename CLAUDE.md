# Dr. Jacobo Núñez Ortiz - Landing Page

## Qué es este proyecto
Landing page para el Dr. Jacobo Núñez Ortiz, especialista en **Otorrinolaringología y Cirugía de Cabeza y Cuello**. Página de presentación profesional para atraer pacientes y permitirles agendar citas.

## Stack
- HTML + CSS + JS vanilla (archivo único `index.html`)
- Sin frameworks ni npm
- Fuente: Outfit (Google Fonts)
- Servidor local: `npx serve` en puerto 3030

## Diseño
- Paleta: Navy profundo `#0b1d3a` + azul acento `#2563eb` + blanco
- Estilo: Moderno, limpio, propositivo - trust-first premium
- Hero: Split asimétrico (texto izquierda, foto derecha)
- Secciones: Hero, Especialidades (bento grid), Sobre el Dr., Contacto, Footer

## Estado actual
- [x] Landing page completa con todas las secciones
- [x] Imágenes placeholder de Unsplash (fotos de médicos reales)
- [x] Formulario de contacto con feedback visual
- [x] Responsive mobile
- [x] Scroll reveal animations
- [ ] Imágenes reales del Dr. Jacobo (pendiente - el doctor debe proveer)
- [ ] Datos de contacto reales (teléfono, correo, dirección del consultorio)
- [ ] Estadísticas reales (años de experiencia, pacientes, cirugías)
- [ ] Integración real del formulario (backend o servicio como Formspree)
- [ ] Generación de imágenes con Replicate/Flux (MCP configurado, pendiente de usar)

## Despliegue
- **Netlify:** desplegado manualmente (drag & drop)
- **GitHub:** https://github.com/raullimher/drjacobo (repo público, rama `main`)
- **Vercel:** pendiente de conectar al repo de GitHub para auto-deploy

## Integraciones configuradas
- **Replicate MCP** conectado en user config global - disponible para generar imágenes con Flux

## Próximos pasos sugeridos
1. Conectar repo GitHub a Vercel para auto-deploy en cada `git push`
2. Generar imágenes con Replicate (foto hero + foto sobre el Dr.) una vez que el Dr. apruebe el placeholder
3. Llenar datos reales de contacto
4. Conectar formulario a un servicio real
5. Considerar agregar sección de ubicación / mapa
