# Setiriň ýarysyna çenli (length / 2) gyrk.
###             I usul
```
function cutWord(text) {
    let s = ""
    let div=Math.floor(text.length/2);
    for (i=div; i<text.length; i++){
        s+=text[i];
    }
    return s
}
console.log(cutWord("RandomText"));
``` 
