# Eger setir 10 nyşandan uzyn bolsa, diňe ilkinji 10 nyşany al.
```
function lengthTen(text) {
    let s=""
    if (text.length<10) {
        return text
    } else {
        for (i=0;i<10; i++){
            s+=text[i];
        }
        return s
    }
}
console.log(lengthTen("Shovket12345678"));
```
