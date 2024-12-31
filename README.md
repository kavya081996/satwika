<!DOCTYPE html>
<html>
    <head>
        <title>Simple JavaScript program</title>
    </head>
    <body>
        <pid="output"></pid>
        <button id="increment-button">Increment</button>
        <script>
            const output=document.getElementById("output");
            const incrementButton=document.getElementById("increment button");
            let count=0;
            incrementButton.addEventListener("click",function){
                count+=1;
                output.innerHTML=count;
            });
        </script>
    </body>
</html>
