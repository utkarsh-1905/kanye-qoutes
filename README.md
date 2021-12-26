# Kanye West Wisdom

**Kanye West** the OG rapper always wanted to spread his wisdom. So, I helped him and created this webpage for _everyone_.

--- ---

You can also create your own page using the this [API](https://api.kanye.rest/). You just need to use an **asynchronous (async/await) function** and fetch the data from the API _(you dont need an API key for this)_ .

```
    async function(){
        const data = await fetch('https://api.kanye.rest/');
        const response = await data.json();
        console.log(response);
    }
```

Your response will look like ``{"quote":"Only free thinkers"}`` which is in JSON format.