# Learn by doing

## Cad filer

her paragrafen som vi ønsker å sortere cad filer i [link til noe](/cad/) :)

- dette er en liste i paragrafen

<div id="minDiv" style="background-color: blueviolet; width: 50px; height: 50px;"></div>

<script>
    let div = document.getElementById("minDiv")
    
    function myFunction()
    {
        if(div.style.backgroundColor == "black"){
            div.style.backgroundColor = "blueviolet"
        }
        else{
            div.style.backgroundColor = "black"
        }
    }

    div.addEventListener('click', myFunction)
</script>