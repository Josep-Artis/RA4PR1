# RA3Ex7 - Activitats ràpides DOM JS

Aquest repositori conté una sèrie d'exercicis pràctics per treballar la manipulació del **Document Object Model (DOM)** utilitzant JavaScript pur.

## Llista d'exercicis i solucions:

A continuació es detallen les tasques realitzades i el codi utilitzat per a cada una:

1.  **Selecció d'elements**: Ús de `querySelector` per canviar el color d'un títol.
    * Solució: `let h1 = document.querySelector("#titol-principal"); h1.style.color ="red";`

2.  **Modificació de contingut**: Canviar el text d'un paràgraf.
    * Solució: `let p1 = document.querySelector("#paragraf-hola"); p1.textContent = "Hola món";`

3.  **Gestió d'atributs**: Canviar la font (`src`) d'una imatge.
    * Solució: `let img1 = document.querySelector("#imatge-canviant"); img1.setAttribute("src", "url_imatge");`

5.  **Alternar classes**: Ús de `classList.toggle` per canviar estils dinàmicament.
    * Solució: `boton.onclick = function() { caixa.classList.toggle("dark-mode"); };`

6.  **Esdeveniments**: Ús de `addEventListener` per disparar alertes.
    * Solució: `botonAlerta.addEventListener("click", function() { alert("pulsaste el boton toggle"); });`

7.  **Creació d'estructura**: Crear nous elements `<li>` i afegir-los a una llista.
    * Solució: `let nouitem = document.createElement("li"); nouitem.textContent = "formatge"; llistaCompra.appendChild(nouitem);`

8.  **Eliminació d'elements**: Esborrar un element del DOM en fer clic.
    * Solució: `cuadroColorSalmon.onclick = function() { cuadroColorSalmon.remove(); };`