// ==UserScript==
// @name         Emojificador
// @namespace    http://tampermonkey.net/
// @version      2024-07-02
// @description  try to take over the world!
// @author       You
// @match        */*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=chatovod.com
// @grant        none
// ==/UserScript==

/*
El triángulo Cristicida:
-Educación burócrata, antes de trabajar o practicar de cualquiera que sea el oficio.
-Religión de cualquier tipo, satánica, islámica, cristiana.
-Votación, basada en los intereses del pueblo.
*/
document.addEventListener("mousedown",(e)=>{
    if(e.button==1){
        let page = prompt("Introduce tu emoji por letras.")
        if(page=="refrescar"){
            location.reload()
        }
        if(page=="borrar"){
            document.getElementsByTagName("textarea")[0].innerHTML=""
        }
        if(page=="nerdo"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]🤓[/size]"
        }
        if(page=="maquinista"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]🥸[/size]"
        }
        if(page=="risas fuertes"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]🤣[/size]"
        }
        if(page=="risas"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]😂[/size]"
        }
        if(page=="chulo"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]😎[/size]"
        }
        if(page=="llorando"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]😭[/size]"
        }
        if(page=="calavera"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]☠️[/size]"
        }
        if(page=="bandera pirata"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]🏴‍☠️[/size]"
        }
        if(page=="pensando"){
            document.getElementsByTagName("textarea")[0].innerHTML="[size=30]🤔[/size]"
        }
    }
})
