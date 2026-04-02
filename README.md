# drapatriciasebelli

Sitio web estatico del consultorio odontologico de la Dra. Patricia Sebelli, con foco en odontologia integral, atencion infantil, FAQ y captacion de consultas.

## Contenido

- `index.html`: landing principal.
- `gracias.html`: pagina de confirmacion posterior al formulario.
- `llms.txt`, `robots.txt`, `sitemap.xml`: soporte SEO y contexto para agentes.
- `hero.mp4`, `logo-clinica.png`, favicons: assets principales.
- `CNAME`: dominio personalizado.

## Funcionalidad

El sitio incluye:

- hero con CTA
- secciones de tratamientos y enfoque de la clinica
- bloque de preguntas frecuentes con datos estructurados tipo FAQ
- formulario de contacto / consulta
- integracion con GTM y Google Analytics

## Stack

- HTML estatico
- CSS embebido
- JavaScript vanilla
- Integraciones externas para analitica y formulario

No requiere build.

## Verlo localmente

```bash
cd drapatriciasebelli
python3 -m http.server 8000
```

Abrir `http://localhost:8000`.

## Deploy

Sitio listo para hosting estatico. Mantener:

- `CNAME`
- `robots.txt`
- `sitemap.xml`
- `llms.txt`

## Notas

- El formulario envia datos a una integracion externa; revisar el endpoint antes de duplicar o migrar el sitio.
- El sitio ya esta optimizado con metadata, canonical y FAQ estructurada.
