# Listas de IPTV Hub

Coloca aquí tus listas **.m3u**, **.m3u8** o **.txt** (también en subcarpetas, hasta 2 niveles).

La app las sincroniza **sola**, cada 6 horas y cada vez que se abre:

- **Archivo nuevo** → se agrega como lista (el nombre del archivo es el nombre de la lista).
- **Archivo modificado** → se vuelve a procesar, conservando favoritos y miniaturas.
- **Archivo borrado** → la lista desaparece de la app.

Sobre cada lista se aplica todo el proceso de la app: categorías, idioma (ES), logos, subtítulos,
películas/series, sin duplicados (misma URL) y sin contenido religioso.

**Enlaces caídos:** se verifican automáticamente y se **eliminan** sin preguntar (con un reintento
para no borrar por un corte momentáneo). Si corriges un enlace en el archivo, vuelve a entrar en la
siguiente sincronización. Los enlaces se vuelven a verificar cada 3 días.

Ejemplo de nombres: `colombia.m3u`, `deportes/futbol.m3u8` → listas "colombia" y "deportes › futbol".
