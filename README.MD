## Primer Taller OpenLab

Primera sesión de ReactJS con 

Colaborador:  [joshDev1205](https://github.com/joshDev1205/ "Colaborador")

### Comandos para iniciar un proyecto en React
- npm init
- npm i react react-dom -S
- npm i -D parcel-bundler babel-preset-env babel-preset-react
- Crear un archivo HTML y crear un elemento con un ID "app" 
- Crear un archivo index.js y escribir el siguiente código 
`import React from 'react'
import {render} from 'react-dom'

class App extends React.Component{
    render(){
        return (<h1> Hola Mundo! edwin </h1>);
    }
}

const mount = document.querySelector('#app')

render(<App/>, mount)`
- Terminar agregando la linea ` "dev": "parcel index.html", ` en "scripts" dentro del package.json
- Terminar con la linea: npm run dev
