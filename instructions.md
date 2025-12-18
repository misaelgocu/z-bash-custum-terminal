# Instruccionews para cambiar de diseño la terminal
Para instalar un nuevo tema lo que debes hacer es ir a esta pagína y descargar con git el repositorio, en el link tenemos el comando pero aun así lo pongo aquí
link: https://github.com/ohmybash/oh-my-bash/tree/master

comando
'''bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"

'''

ahora vamos a este link, en el repositorio tiene la carpeta de themes es lo mismo
link: https://github.com/ohmybash/oh-my-bash/tree/master/themes

ahora si entras en algun tema puede que te pida una fuente, sino te lo pide en el sub-repositorio en un markdown entonces ya es nativo 

aparece algo como esto:
''''
In order for this theme to render correctly, you will need a Powerline-patched font. I recommend: https://github.com/powerline/fonts.git
''''
tienen instalación rápida si entras a su link

algo como:
'''
sudo apt-get install fonts-powerline
'''

Una vez ya este instalado la fuente ahora vamos a la terminal y abrimos bash en la raiz

nano .bashrc
y modificamos la fuente

---


---

# Instrucciones para cambiar de diseño la terminal

Para instalar un nuevo tema lo que debes hacer es ir a esta pagína y descargar con git el repositorio, en el link tenemos el comando pero aun así lo pongo aquí:

**link:** [https://github.com/ohmybash/oh-my-bash/tree/master](https://github.com/ohmybash/oh-my-bash/tree/master)

**comando**

```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"

```

ahora vamos a este link, en el repositorio tiene la carpeta de themes es lo mismo:
**link:** [https://github.com/ohmybash/oh-my-bash/tree/master/themes](https://github.com/ohmybash/oh-my-bash/tree/master/themes)

ahora si entras en algun tema puede que te pida una fuente, sino te lo pide en el subrepo en un markdown entonces ya es nativo.

aparece algo como esto:

> In order for this theme to render correctly, you will need a Powerline-patched font. I recommend: [https://github.com/powerline/fonts.git](https://github.com/powerline/fonts.git)

tienen instalación rápida si entras a su link algo como:

```bash
sudo apt-get install fonts-powerline

```

Una vez ya este instalado la fuente ahora vamos a la terminal y abrimos bash en la raiz:

```bash
nano .bashrc

```

y modificamos la fuente.

---
---

¡Perfecto! Aquí tienes los pasos detallados para editar el archivo y activar el tema que elijas, siguiendo el mismo formato:

### Cómo cambiar el nombre del tema en el archivo

Una vez que ya abriste el archivo con el comando `nano .bashrc`, tienes que buscar la línea que define el tema.

Busca algo como esto:

```bash
OSH_THEME="font"

```

Y simplemente cambias lo que está entre las comillas por el nombre del tema que te gustó de la lista, por ejemplo:

```bash
OSH_THEME="agnoster"

```

**Para guardar los cambios en el editor nano:**

1. Presionas `Ctrl + O` y luego `Enter` para guardar.
2. Presionas `Ctrl + X` para salir del editor.

Finalmente, para que la terminal reconozca el cambio de inmediato sin tener que cerrarla y abrirla de nuevo.