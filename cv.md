# Roman Putilov
## 📲 Contacts
  - Email <PutilovRoman@gmail.com>  
  - Github <https://github.com/putvr>  
  - Discord [@roman-putilov](https://discordapp.com/users/920288291964743710/)

# 🛠 Skills    
  - Linux (Debian, Ubuntu, CentOS, Oracle)
  - Python (Django)
  - DB (Oracle, PostreSQL, MongoDB)
  - HTML / CSS (Bootstrap, pug, SASS/SCSS)
  - Javascript (React)
# 💻 Code example
A simple function that takes a string and returns the string ciphered with Rot13.
```
function rot13(message){
  const input = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz';
  const output = 'NOPQRSTUVWXYZABCDEFGHIJKLMnopqrstuvwxyzabcdefghijklm';

  return message
    .split('')
    .map(e => {
      const i = input.indexOf(e);
      return i > 0 ? output[i] : e; 
    })
    .join('');  
}
```
