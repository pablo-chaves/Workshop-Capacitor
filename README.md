
## Instalación 

Para proyecto desde cero

```bash
  npm init @capacitor/app
  npm i @capacitor/android
  mpn i @capacitor/ios
```

Para SPA existente

```bash
  npm i @capacitor/core
  npm i -D @capacitor/cli
  npm i @capacitor/android
  npm i @capacitor/ios
  npx cap init
```

## Iniciemos nuestro proyecto de Capacitor 

Los siguientes comandos crean nuestra carpeta de android (es obligatorio instalar Android studio)
    
```bash
  npm run build
  npx cap add android
  cap open android
```
Los siguientes comandos crean nuestra carpeta de ios (es obligatorio instalar Xcode - solo para Mac)

```bash
  npm run build
  npx cap add ios
  cap open ios
```