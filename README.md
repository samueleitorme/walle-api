# Walle API

```javascript
const getData() =  async () => {
    try {
        const res = await fetch('https://samueleitorme.github.io/walle-api/characters.json');
        const data = await res.json();
        console.log(data);
    } catch (error) {
        console.error(error);
    }
}

getData()
```

También puedes clonar el repositorio o decargarlo para tenerlo en local. 
```bash
git clone https://github.com/samueleitorme/walle-api.git
```

> Las imágenes las he obteneido de la web https://wayback-api.archive.org/.