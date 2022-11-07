# Votacions
Sistema de votacions amb la cadena de blocs

Instale estos requisitos previos para seguir el tutorial.

MNP: https://nodejs.org
Trufa: https://github.com/trufflesuite/truffle
Ganache: http://truffleframework.com/ganache/
Metamáscara: https://metamask.io/
Paso 1. Clona el proyecto
clon de git https://github.com/Rispiss/Votacions

Paso 2. Instalar dependencias
elección de $ cd
instalación de $ npm
Paso 3. Iniciar Ganache
Abra el cliente GUI de Ganache que descargó e instaló. Esto iniciará su instancia local de blockchain. 

Paso 4. Compile e implemente el contrato inteligente electoral
$ truffle migrate --reset Debes activar el contrato inteligente de elección cada vez que reinicias ganache.

Paso 5. Configurar Metamask
Vea el video tutorial gratuito para una explicación completa de estos pasos:

Desbloquear metamask
Conecte metamask a su cadena de bloques Etherum local proporcionada por Ganache.
Importe una cuenta proporcionada por ganache.
Paso 6. Ejecute la aplicación front-end
$ npm run dev Visite esta URL en su navegador: http://localhost:3000

Si te quedas atascado, consulta el video tutorial gratuito.
