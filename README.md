# SuperVanilla V1.0

SuperVanilla es una configuración competitiva para Left 4 Dead 2 diseñada para partidas 3v3. Esta configuración ajusta varios aspectos del juego para hacerlo más equilibrado y divertido.

## Características
- Límites de armas y objetos
- Configuraciones específicas para cada mapa
- Plugins adicionales para mejorar la experiencia de juego
- Ajustes de dificultad y balance

## Instalación
1. Este modo de juego usa como base el proyecto [L4D2-Competitive-Rework](https://github.com/SirPlease/L4D2-Competitive-Rework) por lo que es necesario instalarlo previamente, de ahí se extraen los complementos básicos para el funcionamiento.
2. Descarga los archivos desde el [repositorio de GitHub](https://github.com/lechuga16/supervanilla).
3. Extrae los archivos en la carpeta principal de tu servidor.
4. Configura los archivos según tus necesidades (ver [Configuración](wiki/Configuración.md)).
5. Reinicia el servidor para aplicar los cambios.

## Configuración

### Agregar modo de juego
El archivo `addons/sourcemod/configs/matchmodes.txt` se usa para mostrar los modos de juego disponibles para iniciar votaciones de uso. Para agregar SuperVanilla a este archivo, agrega lo siguiente:

```plaintext
"MatchModes"
{
    // ...existing code...
    "Super Vanilla Configs"
    {
        "svanilla"
        {
            "name" "Super Vanilla"
        }
        "sv3v3"
        {
            "name" "3v3 Super Vanilla"
        }
        "sv2v2"
        {
            "name" "2v2 Super Vanilla"
        }
        "sv1v1"
        {
            "name" "1v1 Super Vanilla"
        }
    }
    // ...existing code...
}
```

Reinicia el servidor para aplicar los cambios.

## Contribuciones
¡Gracias por tu interés en contribuir a SuperVanilla! Puedes reportar problemas o enviar mejoras a través de la [página de issues](https://github.com/lechuga16/supervanilla/issues) o enviando un pull request en el [repositorio de GitHub](https://github.com/lechuga16/supervanilla/pulls).

## Licencia
SuperVanilla está licenciado bajo la licencia CC-BY-SA 3.0. Para más detalles, consulta el [texto completo de la licencia](http://creativecommons.org/licenses/by-sa/3.0/legalcode).
