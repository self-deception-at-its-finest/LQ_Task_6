# Postman + newman + github actions (Simple store template)

## Download and starting tests
1. Download this repo.
2. Run `npm i` (install node.js dependencies)(node.js version 22 or higher required)
3. Run `npm run tern-on-api`(to run testing server locally )
4. Upload `store.collection.json` and `store.postman-environment.json`in Postman app.
5. Run `store` collection in Postman

### Overview of local server testing
Routes `/products`, `/orders` and `/users`. Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /products     | *None*     | **Array**          |
| GET      | /products/:id |  **e.g 3** | **Object**         |
| POST     | /products     | **object** | **Created object** |
| PUT      | /products     | **object** | **Updated object** |
| DELETE   | /products/:id | **e.g 3**  | **Deleted object** |



###  GH Pages
Collection run results can be seen on github pages: https://self-deception-at-its-finest.github.io/LQ_Task_6/
### Useful links 
Examples with different actions in Postman workspace 
- <a href="https://www.postman.com/postman/workspace/postman-answers"> Postman answers </a>
- <a href="https://restfulapi.net"> REST API Tutorial </a>

Doc for json schema validation, to check output API response
- <a href="https://json-schema.org"> json schema docs </a>
