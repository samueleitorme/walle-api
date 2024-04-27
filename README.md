# Walle API

```javascript
const getData() =  async () => {
    try {

        const res = await fetch('https://walle-api.samueleitorme.github.io');
        const data = await res.json();
        console.log(data);
    } catch (error) {
        console.error(error);
    }
}

getData()
```
