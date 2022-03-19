# Beluga

**Beluga** is a simple style for LaTeX documents. At its core it sets the general layout and typography of the document. On top of the layout, the user can choose between three options, which set the title environment: ```homework```, ```lecture``` and ```paper```. There's also an accompanying minimal preamble.

## Instructions

**Beluga** comes with a custom title environment: ```\belugamaketitle```. If no options are specified when importing the package, ```\belugamaketitle``` automatically falls back to ```\maketitle```. Note that the user can still use ```\maketitle```, since the package doesn't override it.

The options support the following title elements:

| Option | Title elements |
| --- | --- |
| Homework | ```\title```, ```\author```, ```\course```, ```\semester```, ```\shorttitle``` |
| Lecture | ```\title```, ```\author```, ```\lecturer```, ```\course```, ```\semester```, ```\shorttitle``` |
| Paper | ```\title```, ```\author```, ```\affiliation```, ```\email``` |

*Remark:* If left undefined, ```\shorttitle``` automatically falls back to ```\title```. Also ```\title``` and ```\author``` always need to be specified, even if left blank.
