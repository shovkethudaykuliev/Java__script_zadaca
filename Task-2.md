## Berlen sozlemdaki symbollary nache sanydygyny tapmaly bu yerde symbol diyilende sanlar ve harplardan baska hemmesi degisli
```
function  howManySymbol(text) {
    let k=0;
 for(i=0; i<text.length; i++){
    if (!(((text[i].codePointAt(0)>=65)&&(text[i].codePointAt(0)<=90))
            ||
        ((text[i].codePointAt(0)>=97)&&(text[i].codePointAt(0)<=122))
            ||    
        ((text[i].codePointAt(0)>=48)&&(text[i].codePointAt(0)<=56)))
     ){
        k += 1;
    }
 }       
 return k
}
console.log(howManySymbol("Ra@##$@32frgo#24":>:"));
```
