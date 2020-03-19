# Trucos y tips para react-native
Trucos en español para react native

**Lista**

[TOC]


#Crear simulador de ios y correrlo desde consola
*Ideal para cuando tienes escasos recursos*

crear un simulador con un iphone SE
```bash
xcrun simctl create "cheap-simulator" "iPhone SE" "com.apple.CoreSimulator.SimRuntime.iOS-13-3"
```
Iniciarlo desde consola y esperar unos minutos

```bash
xcrun instruments -w "cheap-simulator"  && sleep 120
```

bootear simulador
```bash
xcrun simctl boot cheap-simulator
```

desde el proyecto de react native ejecutar
```bash
npx react-native run-ios --simulator="cheap-simulator"
```

happy codding :headphones:
