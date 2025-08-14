# Eger setiriň uzynlygy > 5 bolsa, soňky 3 nyşany aýyr.
```
function deleteWork(text) {
    let str = ""
    if (text.length>5){
       for (let i=0; i<text.length-3;i++){
        str+=text[i];
       }
    }
    return str
}
console.log(deleteWork("Shovketokuwcy"));
```
