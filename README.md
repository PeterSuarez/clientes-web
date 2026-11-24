# clientes-web
# Paso 1 en un terminal ejecutar los comandos y no se debe cerar 
# direccion clientes-web\api>
cd api
npm test
npm start o npm run dev

# Paso 2 en otro terminar ejecutar los comandos y no se debe cerar
# direccion clientes-web\web>
cd web
ng serve

# Despues de ejecutar ng serve tiene que dar por ejemplo un link como http://localhost:4200/ ese link copiarlo y pegarlo en el buscador siempre va a ejecutar en el puerto 4200

# En aplicacion movil el codigo QR
npx expo start

# En caso que la apk no funcione 
cd movil
npx expo install react-dom react-native-web @expo/metro-runtime
npx expo start --web
