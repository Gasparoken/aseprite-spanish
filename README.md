# Aseprite en Español

Traducción de [Aseprite](https://github.com/aseprite/aseprite) en Español

## Descargar la Extensión

### v0.1.0
Descargar la Extensión Compilada: [Aseprite Spanish v0.1.0](https://github.com/Latirus/aseprite-spanish/releases/download/v0.1.0/aseprite-spanish-v0.1.0.aseprite-extension)

### v0.2.0
¡Actualizado a la version 1.2.34-1 de Aseprite! 

### Básica 
Para instalarlo, descargar el archivo .aseprite-extension en la página de Releases de este Repositorio. https://github.com/Latirus/aseprite-spanish/releases 

#

### Compilando
Clonar este repositorio y ejecutar con Powershell el archivo ubicado en la siguiente carpeta:

```bash
.\src\export.ps1
```

Es necesario contar con PowerShell v5+. Si usas VSCode, con F5 se puede compilar.

Automáticamente se crea la extensión en la siguiente carpeta:

```bash
.\dist\aseprite-spanish-vXXX.aseprite-extension
```

#

## Instalación de la Extensión

Para instalar la Extensión darle doble click al archivo exportado o abrir el archivo desde Aseprite desde el menu de Preferencias.

```
Edit -> Preferences (Ctrl + K) -> Extensions -> Add Extension 
```

Luego, en Preferences (Ctrl + K) / General cambiar Language a:

```
es
```

Es necesario **Reiniciar** el programa para que se apliquen los cambios.

## Contribuir

¡Gracias por considerar contribuir! Podés clonar este repositorio, modificar el archivo:

```
.\src\es.ini
```

Y enviar un **Pull Request** para generar una versión nueva de la traducción.
