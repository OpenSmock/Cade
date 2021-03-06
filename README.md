# Cade

![Slide 16_9 - 1](https://user-images.githubusercontent.com/49183340/177753931-c4c53bd5-86fe-4ef1-82ec-555ee276078e.png)

Cade is a library to build UI prototyping in Pharo.
Cade provide two levels of UI design : the first level is the building of shapes (geometrics, images and texts) and the second level is the building of rich UI with widgets.
Cade is implemented in Cincom VisualWorks since 2010 and also is implemented in Pharo since 2022.

## Overview

-- Mettre vidéos Yann ici --

## Getting Started

### Installing Cade

Pharo 9 and Pharo 10 : 

Cade with Molecule architecture tools :

```smalltalk
Metacello new
   baseline: 'Cade';
   repository: 'github://OpenSmock/Cade';
   load.
```

Cade core :

```smalltalk
Metacello new
   baseline: 'Cade Core';
   repository: 'github://OpenSmock/Cade';
   load.
```

### Prerequisites

Smock toolbox ? TODO

## Credits

* **Pierre Laborde** - *Initial work and development* - [labordep](https://github.com/labordep)
* **Eric Le Pors** - *Initial work and development* - [ELePors](https://github.com/ELePors)
* **Yann Le Goff** - *Development* - [Nyan11](https://github.com/Nyan11)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
