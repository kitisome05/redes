@title[Introduction]

## <span class="gold">Presentación HTTP</span>

<br>
<br>
<span class="byline">[ Características, Típica Sesión, Cabeceras protocolo, Peticiones, Respuestas, Cookies, Evolución ]</span>

---

@title[PITCHME.md]

### <span class="gold">1.-Características del protocolo HTTP</span>
<span class="aside">Hypertext Transfer Protocol</span>
##### Es un sencillo <span class="gold">Protocolo</span> cliente-servidor,
##### escucha en el puerto 80 y el modo seguro es en el 443.
<br>

---

### <span class="gold">2.-Típica Sesión HTTP</span>
##### 1. El cliente establece una conexión TCP.
##### 2. El cliente manda su petición, y espera una respuesta.
##### 3. El servidor procesa la petición, y responde.

---

### <span class="gold">3.- Cabeceras protocolo HTTP</span>
<br>

##### Petición de nuestro navegador.
```shell
GET /index.html HTTP/1.1
Host: www.example.com
User-Agent: nombre-cliente
```

@[1](El cliente hace una petición mediante GET.)
@[2](Dirección a la que hace la petición.)
@[3](Quien hace la petición.)

---

### <span class="gold">3.- Cabeceras protocolo HTTP</span>
<br>

##### El servidor responde a nuestra petición
```shell
HTTP/1.1 200 OK
Date: Fri, 31 Dec 2003 23:59:59 GMT
Content-Type: text/html
Content-Length: 1221
```

@[1](Versión del http y todo salio bien.)
@[2](Fecha de respuesta.)
@[3](Tipo de la respuesta, (text/html))
@[4](El tamaño de la respuesta en octetos.)

---

### <span class="gold">4.- Peticiones HTTP</span>
<br>

#### <span class="gold">GET</span> transmite información atraves de la URL agregando parámetros a la URL.
#### Ejemplo: <span class="aside">/index.php?page=main&lang=es</span>

---
#### No more <span class="gray">Keynote</span>.
#### No more <span class="gray">Powerpoint</span>.
<br>
#### Just <span class="gold">Markdown</span>.
#### Then <span class="gold">Git-Commit</span>.

---

@title[Step 1. PITCHME.md]

### <span class="gold">STEP 1. Create 'PITCHME.md'</span>
<br>
#### Create GitPitch slideshow content using GitHub Flavored Markdown in your favorite editor.
<br>
<span class="aside">It's as easy as README.md with simple slide-delimeters (---)</span>

---

@title[Step 2. Git-Commit]

### <span class="gold">STEP 2. GIT-COMMIT</span>
<br>

```shell
$ git add PITCHME.md
$ git commit -m "New slideshow content."
$ git push

Done!
```

@[1](Add your PITCHME.md slideshow content file.)
@[2](Commit PITCHME.md to your local repo.)
@[3](Push PITCHME.md to your public repo and you're done!)
@[5](Supports GitHub, GitLab, Bitbucket, GitBucket, Gitea, and Gogs.)

---

@title[Step 3. Done!]

### <span class="gold">STEP 3. GET THE WORD OUT!</span>
<br>
![GitPitch Slideshow URLs](assets/images/gp-slideshow-urls.png)
<br>
<br>
#### Instantly use your GitPitch slideshow URL to promote, pitch or present absolutely anything.

---

@title[Slide Rich]

### <span class="gold">Slide Rich</span>

#### Code Presenting for Blocks, Files, and GISTs
#### Image, Video, Chart, and Math Slides
#### Multiple Themes with Easy Customization
<br>
#### <span class="gold">Plus collaboration is built-in...</span>
#### Your Slideshow is Part of Your Project
#### Under Git Version Control within Your Git Repo

---

@title[Feature Rich]

### <span class="gold">Feature Rich</span>

#### Present Online or Offline
#### With Speaker Notes Support
#### Print Presentation as PDF
#### Auto-Generated Table-of-Contents
#### Share Presentation on Twitter or LinkedIn

---

### Go for it.
### Just add <span class="gold">PITCHME.md</span> ;)
<br>
[Click here to learn more...](https://github.com/gitpitch/gitpitch/wiki)
