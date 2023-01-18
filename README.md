# Clone Youtube

Empezamos creando la carpeta del proyecto a travez de npx-create-react-app
Instalamos dependencias:
1-MaterialUI
2-Axios
3-RouterDOM
4-Icons

## Primeros Pasos

Ahora empezamos a darle una estructura mas seria a nuestro proyecto,
borramos la carpeta src que nos instala npx por defecto y creamos una nueva con un Index.js, un App.js y un Index.css

### `BrowserRouter,Routes,Route`

Creamos un BrowserRouter que contenga un Box (MaterialUI), la cual va tener un Routes, con Route, las cuales van a linkear nuestras rutas con nuestros futuros componentes.abs

### `Components`

Creamos una carpeta components con los componentes que usaremos en nuestro clone App. Los cuales son un Feed, un Navbar, un VideoDetail, un ChannelDetail y un SearchFeed.

Para mayor prolijidad, usaremos un index.js donde exportaremos cada componente, el cual nos permite ahorrar y que nuestro codigo sea mas limpio, ya que importamos una sola vez, desde el index dichos componentes.

### `Navbar,SideBar,Feed,Searchbar`

Creamos los componentes para ir dandole forma a nuestra app. En el Navbar incluimos el logo, y una barra de busqueda. Ya en el cuerpo de la App, agregamos un sidebar donde mapeamos las categorias, y los videos.

### `Axios`

Gracias a RapidApi, usando [https://rapidapi.com/ytdlfree/api/youtube-v31](https://rapidapi.com/ytdlfree/api/youtube-v31), utilizamos endpoints para la navegabilidad de la pagina.

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
