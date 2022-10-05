# VANS Chile Tienda
## :purple_heart: Info General
Repositorio que contiene la tienda base (clon) de Vans Chile.

![vans chile](https://user-images.githubusercontent.com/87923794/193928890-1896c3ad-da82-4ee3-aca8-1617e23a49ef.png)


## :wrench: Configuración
### Paso 1 - Configuración básica

Acceda a la [guía de configuración básica](https://vtex.io/docs/getting-started/build-stores-with-store-framework/1) de VTEX IO y siga todos los pasos indicados.

Al final de la configuración, debe tener instalada la interfaz de línea de comandos de VTEX (Toolbelt) junto con un espacio de trabajo de desarrollador en el que puede trabajar.

### Paso 2 - Clonación del repositorio

[Clonar](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) este repositorio en sus archivos locales para poder comenzar a trabajar en él de manera efectiva.

Luego, acceda al directorio del repositorio usando su terminal.

### Paso 3 - Editar el Manifest.json

Una vez en el directorio del repositorio, es hora de editar el archivo `manifest.json` de la plantilla mínima.

Una vez que esté en el archivo, debe reemplazar los valores `vendor` y `name`. `vendor` es el nombre de la cuenta del partner en la que está trabajando y `name` es cualquier nombre que desee para su tema. Por ejemplo:

```json
{
  "vendor": "partner",
  "name": "store--name",
}
```

### Paso 4 - Instalar apps necesarias

Para usar Store Framework y trabajar en el tema de su tienda, es necesario tener instalados `vtex.store-sitemap` y `vtex.store`.

Ejecute `vtex list` y verifique si esas aplicaciones ya están instaladas.

Si no lo están, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 - Desinstalar el store-theme predeterminado

Al ejecutar `vtex list`, puede verificar si algún tema está instalado.

Es común tener ya instalado un `vtex.store-theme` cuando inicia el proceso de desarrollo frontal de la tienda.

Por lo tanto, si lo encuentra en la lista de aplicaciones, copie su nombre y version, luego utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme@0.0.1
```

### Paso 6 - Ejecute un preview de la tienda

Entonces ha llegado el momento de cargar todos los cambios que realizó en sus archivos locales a la plataforma. Para eso, use el comando `vtex link`.

Si el proceso se ejecuta sin ningún error, se mostrará el siguiente mensaje: `Aplicación vinculada con éxito`. Luego, ejecute el comando `vtex browser` para abrir una ventana del navegador que tenga su tienda vinculada.

Esto le permitirá ver los cambios aplicados en tiempo real, a través de la cuenta y el espacio de trabajo en el que está trabajando.

## :large_orange_diamond:Builders
1. "assets": "0.x"
2. "styles": "2.x"
3. "store": "0.x"
4. "docs": "0.x"

## :electric_plug:Store Components
1.  "vtex.store": "2.x"
2.  "vtex.store-header": "2.x"
3.  "vtex.product-summary": "2.x"
4.  "vtex.store-footer": "2.x"
5.  "vtex.store-components": "3.x"
6.  "vtex.styleguide": "9.x"
7.  "vtex.slider": "0.x"
8.  "vtex.carousel": "2.x"
9.  "vtex.shelf": "1.x"
10. "vtex.menu": "2.x"
11. "vtex.minicart": "2.x"
12. "vtex.product-details": "1.x"
13. "vtex.product-kit": "1.x"
14. "vtex.search-result": "3.x"
15. "vtex.login": "2.x"
16. "vtex.my-account": "1.x"
17. "vtex.flex-layout": "0.x"
18. "vtex.rich-text": "0.x"
19. "vtex.store-drawer": "0.x"
20. "vtex.locale-switcher": "0.x"
21. "vtex.product-quantity": "1.x"
22. "vtex.product-identifier": "0.x"
23. "vtex.product-specification-badges": "0.x"
24. "vtex.product-review-interfaces": "1.x"
25. "vtex.telemarketing": "2.x"
26. "vtex.order-placed": "2.x"
27. "vtex.stack-layout": "0.x"
28. "vtex.tab-layout": "0.x"
29. "vtex.responsive-layout": "0.x"
30. "vtex.slider-layout": "0.x"
31. "vtex.iframe": "0.x"
32. "vtex.breadcrumb": "1.x"
33. "vtex.sticky-layout": "0.x"
34. "vtex.add-to-cart-button": "0.x"
35. "vtex.store-newsletter": "1.x"
36. "vtex.store-icons": "0.x"
37. "vtex.product-list": "0.x"
38. "vtex.disclosure-layout": "1.x"
39. "vtex.store-image": "0.x"
40. "vtex.product-price": "1.x"
41. "vtex.store-link": "0.x"
42. "vtex.modal-layout": "0.x"
43. "vtex.product-highlights": "2.x"
44. "vtex.product-specifications": "1.x"

## :zap:Custom Apps
1. "itgloberspartnercl.whatsapp-button": "0.x"
2. "itgloberspartnercl.bullets-diagramation": "0.x"
3. "itgloberspartnercl.add-to-cart-info": "0.x"
4. "itgloberspartnercl.custom-department-search": "0.x"
5. "itgloberspartnercl.pdf-reader": "0.x"
6. "itgloberspartnercl.quick-order": "0.x"
7. "itgloberspartnercl.special-diagramation": "0.x"

## :space_invader:Colaboradores
- Carolina Araya González
