# sözleriň sanawyndan her biriniň ilkinji harplaryndan täze setir döret.
```
function firstSymbol(text) {
    text+=" ";
    let str = "";
    for (i=0; i<text.length; i++){
        if(text[i]!=" "){
            str+=text[i];
        } else if (str!=""){
            console.log(str[0]);    
            str="";        
        }
    }
}
firstSymbol("Hello how are you What are you doing");
```
