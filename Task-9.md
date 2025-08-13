# Sanawdaky her bir sözüň uzynlygyny görkez.
```
function wordLength(text) {
    while(text.indexOf('  ')>-1){
        text= text.replace("  "," ")
    }
    text+=" "; let str=""
    for (i=0; i<text.length; i++){
        if (text[i]!=" "){
            str+=text[i];
            } else if (str!="") {
            console.log(str.length);            
            str=""
        }
    } 
}
wordLength("itrmrtin                            erfkterokferr                rtdfgttreefgrerfdg                        rtdfsdre")
```
