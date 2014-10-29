---
title: Your own course
published: true
---

<!--# Your Very Own Course! Ideas + Technical Bits-->

# ¡Armando el curso! Ideas + bits técnicos

![Image of maze with starting point indicated]({{site.baseurl}}/img/start.jpg)

Imagen [CC-BY-SA](https://creativecommons.org/licenses/by-sa/2.0/) de [mikecogh](https://www.flickr.com/photos/mikecogh/11300349426) en Flickr.

<!--During this course you will learn the theoretical and technical parts by creating your own online course! [Applause](http://media.giphy.com/media/Hc8PMCBjo9BXa/giphy.gif)!
-->
¡Durante este curso aprenderán las partes técnicas y teóricas a traves de la creación de sus propios cursos!
¡[Aplausos](http://media.giphy.com/media/Hc8PMCBjo9BXa/giphy.gif)!

<!--
## Steps to Get Your Own Course
### Copy this course.
This course is built using [GitHub Pages](https://pages.github.com/), to make a copy of this course, you need to fork the repository on GitHub. You can do this by clicking the link below. You may need to log in or create a GitHub account.

<a class="btn btn-primary" href="https://github.com/p2pu/course-in-a-box/fork" target="_blank"><i class="fa fa-code-fork"></i> Copien este curso</a>

This copy is where you will be working during the rest course. Some of the technical things may be challenging or frustrating, but by tackling it bit by bit and asking your peers for help, you’ll soon be an expert and helping other people!
-->

## Pasos para armar su propio curso
### Copien este curso
Este curso está construido usando las [Páginas de GitHub](https://pages.github.com/), para hacer una copia de este curso, necesitan *forkear*, hacer una copia o bifurcación del repositorio en GitHub.
Pueden hacer esto haciendo click en el link de acá abajo. Es probable que tengan que loguearse o crear una cuenta en GitHub.

<a class="btn btn-primary" href="https://github.com/acercadelaeducacion/course-in-a-box/fork" target="_blank"><i class="fa fa-code-fork"></i> Copiar este curso</a>

Esta copia es en la que trabajaran durante el resto del curso. Algunas de las cuestiones técnicas pueden representar desafíos o resultar frustrantes. Pero abordandolas paso a paso, sonsultando y pidiendo ayudas a sus pares, pronto se convertiran en expertos/as y estaran ayudando a otras personas.

<!--### Tweak a few items. 
There are two updates that you need to make to your course to get it working. First, change

{% highlight yaml %}baseurl:{% endhighlight %}

to

{% highlight yaml %}baseurl: /course-in-a-box{% endhighlight %}

in the file [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_config.yml](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_config.yml)

Next, delete the file called CNAME [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/CNAME](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/CNAME)

Now that you have a space to work, lets put a draft framework in place for your course.
-->

### Ajuste de algunos elementos
Hay dos actualizaciones o modificaciones que tienen que hacerle al curso para tenerlo en funcionamiento. Primero cambien

{% highlight yaml %}baseurl:{% endhighlight %}

a

{% highlight yaml %}baseurl: /course-in-a-box{% endhighlight %}

en el archivo [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_config.yml](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_config.yml)

Luego, borren el archivo llamado CNAME [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/CNAME](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/CNAME)

Ahora que tienen un espacio de trabajo, hagamos un borrador del marco de trabajo del curso

<!--
### Give your course a name. 
To update the title of your course, go to [https://github.com/your-github-username/course-in-a-box/](https://github.com/your-github-username/course-in-a-box/edit/gh-pages/_data/course.yml) and edit the file called `_data/course.yml`. You will see the title for this course there, change that to the name you decided on. Don't worry too much if you don't have the perfect name, you now know how to change the title for your course and you can update it at any time!

{% highlight yaml %}title: "Course Title"{% endhighlight %}
-->
### Denle al curso un nombre
Para modificar el título del curso, vayan a
[https://github.com/your-github-username/course-in-a-box/](https://github.com/your-github-username/course-in-a-box/edit/gh-pages/_data/course.yml) y editen el archivo llamado `_data/course.yml`. Verán el título de este curso ahí, cambienlo al nombre que quieran para su curso. No se preocupen demasiado si no tienen el nombre perfecto. Ahora que ya saben como cambiar el título de su curso pueden hacerlo en cualquier momento.

{% highlight yaml %}title: "Course Title"{% endhighlight %}

<!--
### Who is the course for & what will they learn?
Will they be building something during the course. Put this basic information on the front page of the course to give a short overview of what to expect. To update the info on the front page, go to the file [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) and replace the text currently there to reflect what your course will be about. Once again, you can update it at any time and we will come back to this at a later stage.
-->
### ¿Para quién es el curso y que aprenderán en él?
¿Contruirán algo durante el curso?. Pongan la información básica en la página que incio del curso para que tengan un vestazo de lo que harán. Para actualizar la información en la *página de inicio*, vayan al archivo  [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) y remplacen el texto actual a uno que refleje de qué se tratara su curso. Como se dijo anteriormente, pueden cambiar esto en cualquier momento, más adelante volveremos más adelante volveremos sobre este tema.

<!--
### Lets have a look at your course!

You can view it by going to [https://your-github-username.github.io/course-in-a-box/](https://your-github-username.github.io/course-in-a-box/), just replace your-github-username with your GitHub username.
-->
### ¡Veamos cómo va quedando el curso!
Pueden verlo yendo a [https://your-github-username.github.io/course-in-a-box/](https://your-github-username.github.io/course-in-a-box/), solo remplacen *your-github-username* con el nombre de usuario de GitHub. 

<!--
## Resources and Help

- See our <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">GitHub Cheatsheet</a> if you get stuck with any git related things. 
- Ask a question on the [P2PU community forum](http://community.p2pu.org/category/tech).

You may have noticed that the [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) file contained a few funny caracters. This is called [Markdown](https://en.wikipedia.org/wiki/Markdown), an easy way of writing files for the web. For some tips on how to get the most out of Markdown, see [our Markdown cheetsheet]({{site.baseurl}}/references/markdown-cheatsheet/).
 
**Possible error: pages not displayed.** You can get an email after forking the repository with the following message: "The page build failed with the following error: Page build failed". To solve this issue, check you have [enabled the automatic page generator](https://help.github.com/articles/creating-pages-with-the-automatic-generator) on your repository. Another possible cause would be a missing whitespace in your newly added content. Double check it and commit again to trigger page generation.
-->
## Recursos y ayudas
- Chequeen nuestro <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">Machete de GitHub</a> si se quedan trabadxs con cualquier cosa relacionada a git. 
- Pregunten en el [foro de la comunidad P2PU](http://community.p2pu.org/category/tech).
- Se habran dado cuenta que el archivo [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) contiene algunos caracteres raros. Esto se llama [Markdown](https://es.wikipedia.org/wiki/Markdown), una forma sencilla de escribir paginas en la  web. Para tener algunos tips sobre como sacar el mejor provecho de Markdown vean [nuestro machete de Markdown]({{site.baseurl}}/references/markdown-cheatsheet/).
 
**Posibles errores: pages not displayed.** Puede ser que les llegue un mail despues de forkear el repositorio con el siguiente mensaje en inglése: "The page build failed with the following error: Page build failed". Para resolver este problema, chequeen que tienen habilitado el generador de páginas automáticas en inglés:  ["automatic page generator"](https://help.github.com/articles/creating-pages-with-the-automatic-generator) en su repositorio. Otra posible causa de este es que falte un espacio en blanco en los contenidos nuevos que agregaron. Chequeen nuevamente si cuando cambiaron el títlulo de la página o la descripsión dejaron un espacio en blanco entre los **:** y su nuevo contenido.
