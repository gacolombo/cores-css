# CORES

Usamos CSS para alterar cores do nosso documento.

## TIPOS

* background-color (para caixas);
* color (textos);
* border-color (para caixas);
* outros...

## VALORES

Podemos definir os valores por

* palavra-chave (blue, transparent);
* hexadecimal (#990011);
* funções: rgb, rgba, hsl, hsla.

```css
element{
    /* Keyword values */
    color: currentcolor;

    /* <name-color> values */

    color: red;
    color: orange;
    color: tan;
    color: rebeccapurple;

    /* <hex-color> values 0-F */
    color:#090;
    color:#009900;
    color:#090a;
    color:#009900aa;

    /* <rgb()> values */
    color:rgb(34, 12, 64, 0.6);
    color:rgba(34, 12, 64, 0.6);
    color:rgb(34 12 64 / 0.6);
    color:rgba(34 12 64 / 0.3);
    color:rgb(34.0 12 64 / 60%);
    color:rgba(34.0 12 64 / 30%);

    /* <hsl()> values */
    color: hsl(30, 100%, 50%, 0.6);
    color: hsla(30, 100%, 50%, 0.6;
    color: hsl(30 100% 50% / 0.6);
    color: hsla(30 100% 50% / 0.6);
    color: hsl(30 100% 50% / 60%);
    color: hsla(30 100% 50% / 60%);

     /* Global Values */
     color: inherit;
     color: initial;
     color: unset;

}

```