# Caturday Debug

## Main Focus:
<p> This fireside primarily focuses on tips and tricks for debugging vue, it also serves as an overarching review before their checkpoint </p>
<br>
A list of what'll be broken in the starting branch can be found below
<hr>

​
* Home page - import AppState as Appstate (creating a second appstate)
* Home page - prop passes whole collection
* Home page - prop passed is not data bound
* CatComponent - prop name is incorrect
* CatComponent - props are not taken in on setup
* CatComponent - v-for does not have a key
* CatComponent - Use Route isn't imported
* Router index.js - id on factpage is not bound
* CatService - exporting as catsService instead of catService
* CatComponent - Cat data is not referencing the state before it references the fact incorrectly
* CatService - Response res.data needs to be res.data.data (ALWAYS CHECK THE RESPONSE FROM THE SERVER)
* Axios Service - base url for api puts a / before the query
* Axios Service - base url is missing Https from api request, causing a CORS error