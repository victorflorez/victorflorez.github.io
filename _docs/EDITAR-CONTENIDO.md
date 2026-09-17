# Editar contenido sin código

1. Abre https://app.pagescms.org e inicia sesión con GitHub.
2. La primera vez, autoriza Pages CMS únicamente para `victorflorez.github.io`.
3. Selecciona ese repositorio y la rama `master`.
4. Abre **Publicaciones**. Añade un elemento con el año, la referencia completa y el enlace. No escribas el número inicial: la página lo calcula.
5. Guarda. El guardado actualiza la página pública cuando termina GitHub Pages; no es solo un borrador.

La lista permite reordenar las referencias dentro del mismo año. No borres publicaciones para añadir otra. Antes de guardar, revisa la referencia y el enlace.

En **Biografía y hoja de vida** puedes editar la biografía de la portada en ambos idiomas y seleccionar/subir el PDF del CV. El PDF guardado se usa tanto en la portada como en el perfil académico. Los archivos subidos al sitio son públicos.

El editor requiere iniciar sesión; el sitio público no guarda contraseñas ni tokens. La autorización inicial de Pages CMS la realiza el propietario en GitHub. La conexión de GitHub con ChatGPT es independiente.

## Dónde están los datos

- `_data/publications.json`: referencias.
- `_data/profile.json`: biografía y dirección del CV.
- `.pages.yml`: definición del formulario.
- `publications.html`: presentación, sin referencias escritas dentro.

La lista anterior estaba en `_posts/2023-07-28-Publications.md`. Ese archivo ahora lee la misma lista de datos, para evitar duplicados que queden desactualizados.
