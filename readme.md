# Flex-box

## Contenedor

**Para utilizar flex-box solo se necesita indicar la propiedad display**

    .contenedor {
        display: flex;
    }

**Dirección de los elementos dentro del contendor y su eje principal**

    .contenedor {
        display: flex;
        flex-direction: row | row-reverse | column | column-reverse;
    }

**Para indicar si todos los elementos del contenedor perteneceran a una sola linea o varias**

    .contenedor {
        display: flex;
        flex-wrap: nowrap | wrap | wrap-reverse
    }

**Para alinear los elementos en su eje principal**

    .contenedor {
        display: flex;
        justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;
    }

**Para alinear los elementos en su eje secundario**

    .contenedor {
        display: flex;
        align-items: flex-start | flex-end | center | baseline;
    }

**Para alinear los elementos en su eje principal di hay mas de una fila**

    .contenedor {
        display: flex;
        align-content: stretch | flex-start | flex-end | center | space-between | space-around;
    }

## Elemento

**Para alinear un solo elemento**

    .elmento {
      align-self: auto | stretch | flex-start | flex-end | center | baseline;
    }

**Tamaño de los elementos**

    .elemento {
      flex-grow: number;
      flex-shrink: number;
      flex-basis: number[px, rem, em...]
      flex: flex-grow flex-shink flex-basis;
    }

**Para reordenar elementos**

    .elemento {
      order: number
    }
