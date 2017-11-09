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

### <span class="gold">5.- Respuestas HTTP</span>
<br>

#### <span class="gray">1XX</span> Respuestas informativas
#### <span class="gray">2XX</span> Peticiones correctas
#### <span class="gray">3XX</span> Redirecciones
#### <span class="gray">4XX</span> Errores del cliente
#### <span class="gray">5XX</span> Errores del servidor

---

### <span class="gold">6.- Cookies</span>
<br>

#### Las cookies fueron diseñadas para ser un mecanismo confiable para que los sitios web recuerden información con estado (como elementos agregados en el carro de compras en una tienda en línea) o para registrar la actividad de navegación del usuario (incluyendo hacer clic en botones particulares, iniciar sesión...

---

### <span class="gold">7.- Evolución de HTTP</span>
<br>

#### -Empezó en el 1990 con la versión HTTP 0.9
#### -Luego prosiguió hasta la versión HTTP 1.1 y fue evolucionando unos 15 años.
#### -Y por último tenemos la versión HTTP/2 que fue lanzada en mayo 2015.

---

### <span class="gold">8.- Características de HTTP 2.0</span>
<br>

#### -<span class="gold">Alt-Svc</span> Permite disociar la identificación de una ubicación, con respecto a un recurso pedido.
#### -<span class="gold">Client-Hints</span> Permíte al navegador, o cliente, comunicar proactivamente al servidor.
#### -La introducción de prefijos de seguridad en la cabecera <span class="gold">Cookies</span>
