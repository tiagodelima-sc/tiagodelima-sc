# deisantix.js

```js
const tiagoschermack = {
    name: ['Tiago', 'De Lima'],
    pronouns: ['he/him', 'ele/dele'],
    from: Brazil,
    
    languages: [Python, Java, PHP, HTML, CSS, JavaScript],
    learning: [Django, Flask, MySql, CherryPy],
    
    hobbies: [reading, cycling, playing soccer, walking],
    sports: [soccer],
    
    speak: function() {
        return 'portuguese' || 'english';
    },
    procrastinate: function() {
        alert("Just one more minute...");
    },
    study: function() {
        alert("I'm studying" + this.learning);
    }
}
if(Date.time > 0) {
    tiagoschermack.procrastinate();
} else {
    tiagoschermack.study();
}
```
