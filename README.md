## Revealer.js

A multi-user Reveal.js presentation server using Express.js and Socket.IO.

This is the complete code used in the http://www.sitepoint.com/create-multi-user-presentation-reveal-js/ article.  

To try

```
$ git clone https://github.com/shameerc/Revealer.js.git
$ npm install && bower install
$ grunt
```

Server will start running in `http://localhost:3000`. You can take this url and login
with username=username and password=password. Other clients can connect to `http://localhost:3000/client` to see the presentation.

###Demo
Master : http://revealerjs-9398.onmodulus.net/  
 `username = username` & `password=password`  
Client : http://revealerjs-9398.onmodulus.net/client

**Note : You may need to update `host` in `public/js/config.js` when it's not in localhost.**
