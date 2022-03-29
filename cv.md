# Oksana Semenova

## Contacts
**E-mail:** oxanacode@gmail.com
**Telegram:** @oxvsem

## Code example
```javascript
function encode(word){  
  let simbols = word.toLowerCase().split(''); 
  return simbols
          .map(a => simbols.includes(a, simbols.indexOf(a)+1) ? ')' :'(')
          .join('');
}
```
## Education

