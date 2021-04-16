## Route parameter

#### http://localhost:3000/movies/star%wars 

#### Access it in Express
```js
// app.js
app.get('/movies/:title, (req, res) => {
    console.log(req.params.title)
})
```

## Query String

#### http://localhost:3000/movies?title=star%wars

#### Access it in Express
```js
// app.js
app.get('/movies, (req, res) => {
    console.log(req.query.title)
})
```