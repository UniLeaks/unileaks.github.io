# Blog sobre la UNRC.

Usando [Jekyll](https://jekyllrb.com/) y el tema [So Simple](https://github.com/mmistakes/so-simple-theme)

## Instalación

Como super usuario:  

```
gem install jekyll-theme-so-simple
```

## Build

O como general el `_site`:  

```
# nos genera el _site
jekyll build

# nos re-genera cuando modificamos el sitio
# util para probar!
# no funciona se toca el _config.yml
jekyll serve

# otras cosas utiles:
# --future nos muestra post cuya fecha esten en el futuro
jekyll --future build 

# --drafts nos muestra los post que esten en el dir
# _drafts (los borradores).
jekyll --drafts build
```

Mas info en la [doc](https://jekyllrb.com/docs)

## Estructura

Las cosas importantes:

`_config.yml`: configuración del sitio.  
` _posts`: directorio donde van los post. Tienen que comenzar con la  fecha los nombres, como `AÑO-MES-DIA-nombre-del-archivo.md`  
`_drafts`: Trabajos en progreso (similar a `_posts`, pero solo se muestran cuando se hace el build con `--drafts`. Cuando estén listos se mueven a `_posts`  
`_site`: El sito generado por jekyll  

## Task list

- [x] Hacer la task list
- [ ] Agregar `logo` al _config.yml
- [ ] Agregar `picture` al Site Author en _config.yml
- [ ] Agregar licencia en el footer.
- [ ] Agregar links al contacto en el footer
- [ ] Sacar rss.
- [ ] Sacar botones de compartir en Linkedin y en Reddit.
- [x] Agregar las paginas linkeadas arriba (navigation)
