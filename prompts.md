"Construi un Pomodoro. Estilo: que se parezca al menu de un videojuego. Constraints: un archivo, vanilla JS, sin deps"

Prompt de inicio, descripcion de estilo muy general solo para ir con la tematica.

"Adapta el pomodoro para que para hacerle click a cualquiera de sus botones haya que clickear un poco mas abajo a la derecho que donde el boton esta realmente"

Base de la idea, desalineacion de los botones. Este y los promps siguientes me despuestran que cierta falta de especificacion me traeran problemas.

"Adapta el pomodoro para que la hitbox sea mucho mas abajo, que ni siquiera se superponga con el boton"

Otro error de especificacion, solo digo que tiene que se mas abajo, pero no mas a la derecha, lo cual me deja con los botones y su hitbox alineadas en su verticalidad.

"Ahora adapta el pomodoro para que la hitbox esta considerablemente mas a la derecha"

Solucion del error anterior.

"Ahora adapta el pomodoro para que ya no se pueda escribir sobre las casillas de focus min, break min y long break, solo modificarlas con los botones de aumentar y reducir"

Para experimentar lo horrible que puede ser este simple error, quise limitar las facilidades de algunos botonos, estos cambios no se implantaron correctamente y pase los prompts siguientes intentando arregralos o romperlos en este caso.

"En <section class="settings" aria-label="Configuración del Pomodoro"> que cada seccion se pueda aumentar o bajar de valor con botones para cada una"

Especificando la seccion intento solucionar mi dilema, buen enfoque, no exactamente lo que queria, resulto en una desaparicion de la casilla en su totalidad.

"Adapta cada una de esas secciones para que solo se puedan cambiar con los built-in spinner controls y no se les pueda escribir encima"

Despues de buscar especificamente el codigo que genera esa seccion, y de preguntar a chatgpt en otra ventana como se generan esos botones, me entero que se llaman built-in spinner controls, con esta especificacion, la creacion se da de forma correcta.

