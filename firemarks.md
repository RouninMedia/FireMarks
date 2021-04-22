**Remove Links to Stack Overflow Meta**
    
    javascript:(()=>{[...document.querySelectorAll('[href^="https://meta.stackoverflow.com/"]')].forEach((link)=>{link.remove()})})();
