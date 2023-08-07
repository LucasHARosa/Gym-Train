Fontes:

npx expo install expo-font @expo-google-fonts/roboto

Native base, componentes
npm install native-base     

não sei para que serve:
expo install react-native-safe-area-context@3.3.2  
npm install --save-dev babel-plugin-module-resolver

Para usar svg:
npm i react-native-svg-transformer --save-dev

navegação:
npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/native-stack

imagem picker
npx expo install expo-image-picker
em app.json para permissão
{
  "expo": {
    "plugins": [
      [
        "expo-image-picker",
        {
          "photosPermission": "The app accesses your photos to let you share them with your friends."
        }
      ]
    ]
  }
}
 
par limitar o tamanho dos dados
npx expo install expo-file-system