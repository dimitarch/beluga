# Beluga

**Beluga** is a simple style for LaTeX documents. At its core it sets the layout and typography of the document. It supports the following self-explanatory options: ```homework```, ```lecture``` and ```paper```. It comes with an accompanying preamble.

## Instructions

**Beluga** comes with a custom title environment: ```\belugamaketitle```. If no options are specified when importing the package, ```\belugamaketitle``` automatically falls back to ```\maketitle```. One can still use ```\maketitle```, since the package doesn't override it.

The options support the following title elements:

| Option | Title elements |
| --- | --- |
| Homework | ```\title```, ```\author```, ```\course```, ```\semester```, ```\shorttitle``` |
| Lecture | ```\title```, ```\author```, ```\lecturer```, ```\course```, ```\semester```, ```\shorttitle``` |
| Paper | ```\title```, ```\author```, ```\affiliation```, ```\email``` |

Note that if left undefined, ```\shorttitle``` automatically falls back to ```\title```.

## Note on the Name

The inspiration behind the name are Belugas (Delphinapterus leucas), also known as white whales, sea canary or melonhead, however, it has no connection to the actual contents of the style. It just sounds cool! As you might have guessed I might have a slight obsession with whales.
