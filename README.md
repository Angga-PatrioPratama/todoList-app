## Description
react todo app with CRUD operation with json-server

## Tech Stack
**Client:** React js , Bootstrap

**Server:** json server

## Packages
| Package | Useage |
| ------ | ------ |
| [json-server](https://github.com/typicode/json-server) | use for simulate backend |
| [axios](https://axios-http.com/) | for create HTTP request better and smoother |
| [Bootstrap](https://www.npmjs.com/package/bootstrap) | for styling |
| [Bootstrap-icons](https://icons.getbootstrap.com/) | for icons |
| [uuidv4](https://www.npmjs.com/package/uuidv4) | for create unique key for list rendering |
| [react-toastify](https://www.npmjs.com/package/react-toastify) | for create toast-notification |
| [concurrently](https://www.npmjs.com/package/concurrently) | for run multiple scripts simultaneously with one script |

## How to begin
$ npm i
$ npm start

it may take a little long to run for first time , so wait till the browser showup!

> with concurrently package , the "npm start" in "create-react-app" is equal to run this following commands:
```sh
npm start = npm start(create-react-app default) + json-server --watch db.json
```