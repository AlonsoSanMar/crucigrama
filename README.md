# Crucigrama
## **Generar tu propio crucigrama** 💡

Con esta herramienta podremos cargar la estructura deseada para armar nuestro propio **crucigrama personalizado**. El crucigrama debe respetar el **formato JSON**, con la estructura que se presenta a continuación. También, se incluye un JSON de ejemplo. Con sólo modificar los valores del JSON de ejemplo, se puede obtener un nuevo crucigrama.

Accede a la herramienta [haciendo clic aquí](https://m0nt4ld0.github.io/crucigrama/).

![image](https://github.com/user-attachments/assets/d6b948e3-97ff-4738-8f10-0515ac57b297)

El JSON a insertar debe contener el siguiente formato:

- **vword**: Es la palabra a modo de "pista" que se muestra verticalmente.
- **refs**: Arreglo con las referencias del crucigrama (descripciones a modo de "pista" para que el jugador intente adivinar la palabra.
- **answers**: Arreglo con las palabras de respuesta.

A continuación, se presenta un ejemplo:

```
[
  {
     "vword": "Freud",
     "refs": [
        "Antigua teoría pseudocientífica, hoy sin validez, que afirmaba poder determinar rasgos del cáracter y de la personalidad basándose en la forma del cráneo y las facciones.",
        "Fuerza que durante el análisis «se defiende por todos los medios contra la curación y a toda costa quiere aferrarse a la enfermedad y el padecimiento»",
        "Complejo de...",
        "Fuente de estímulos en constante fluir, procedente de una excitación interna (a diferencia del estímulo que es externo) y está ligada a un objeto, el cual es transitorio. Su satisfacción es parcial.",
        "Proyección, introyección, identificación proyectiva, todos estos son mecanismos de..."
     ],
     "answers": [
        "frenologia",
        "resistencia",
        "edipo",
        "pulsion",
        "defensa"       
     ]
  }
]
```
Este JSON dará lugar al siguiente crucigrama:

![image](https://github.com/user-attachments/assets/c9478e37-1f0a-4a0e-9260-5c45e713d6e3)

## **Imprimir el crucigrama** 🖨️
Una vez cargado el crucigrama personalizado, podremos imprimirlo haciendo clic en el botón correspondiente. Nos va a abrir una nueva página en blanco, con el crucigrama para completarlo y sus referencias. Podemos imprimirlo, o guardarlo en nuestro equipo como un documento PDF.

Clic en el botón **Imprimir**
![image](https://github.com/user-attachments/assets/e7f20174-c0e0-4fe5-b842-3612a6768fd7)

Se abre la siguiente página, para la impresión. En el cuadro de selección de la derecha podemos alternar entre imprimirlo (con nuestra impresora instalada y configurada) o guardarlo como PDF.

![image](https://github.com/user-attachments/assets/12a88238-b609-42be-a203-69f1f96f4de0)

---
**Here the english reference started.**

# Crossword
## **Generate your own crossword** 💡

With this tool we can load the desired structure to create our own **personalized crossword**. The crossword must respect the **JSON format**, with the structure presented below. Also, an example JSON is included. By simply modifying the values ​​of the example JSON, you can obtain a new crossword puzzle.

Access the tool [by clicking here](https://m0nt4ld0.github.io/crucigrama/).

![image](https://github.com/user-attachments/assets/d6b948e3-97ff-4738-8f10-0515ac57b297)

The JSON to be inserted must contain the following format:

- **vword**: It is the word as a "hint" that is displayed vertically.
- **refs**: Fix with the crossword puzzle references (descriptions as a "clue" for the player to try to guess the word.
- **answers**: Fix with response words.

Below is an example:

```
[
  {
     "vword": "Freud",
     "refs": [
        "Ancient pseudoscientific theory, now invalid, that claimed to be able to determine character and personality traits based on the shape of the skull and facial features.",
        "Force that during the analysis «defends itself by all means against the cure and at all costs wants to cling to the illness and the suffering»",
        "Complex of...",
        "Source of stimuli in constant flow, coming from an internal excitation (unlike the stimulus that is external) and is linked to an object, which is transitory. Its satisfaction is partial.",
        "Projection, introjection, projective identification, these are all mechanisms of..."
     ],
     "answers": [
        "phrenology",
        "endurance",
        "Oedipus",
        "drive",
        "defense"       
     ]
  }
]
```
This JSON will result in the following crossword puzzle:

![image](https://github.com/user-attachments/assets/c9478e37-1f0a-4a0e-9260-5c45e713d6e3)

## **Print the crossword** 🖨️
Once the personalized crossword puzzle is loaded, we can print it by clicking on the corresponding button. It will open a new blank page, with the crossword puzzle to complete and its references. We can print it, or save it on our computer as a PDF document.

Click on the **Print** button
![image](https://github.com/user-attachments/assets/e7f20174-c0e0-4fe5-b842-3612a6768fd7)

The next page opens, for printing. In the selection box on the right we can toggle between printing it (with our printer installed and configured) or saving it as a PDF.

![image](https://github.com/user-attachments/assets/12a88238-b609-42be-a203-69f1f96f4de0)