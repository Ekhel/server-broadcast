![Flickr](https://live.staticflickr.com/65535/49756424827_a7a5c21b3c_b.jpg)

<p align="center">
    <h3>SERVER DB JSON & API Streams Backend </h3>
</p>

## Deskripsi Praktek :
* Simple Server dan Database API Conventions yang di tampung dalam npmjs (json-server)

----------------------------------------------------------------------------------------------------------

## Library :

| Library           | Package Instalation                                                               |
| ---------------   | --------------------------------------------------------------------------------- |
| npm init          | *npm init*                                                                        |
| json-server       | *npm install --save json-server*                                                  |

--------------------------------------------------------------------------------------------------------------

## Soure Pendukung :
* npmjs : ![json-server](https://www.npmjs.com/package/json-server)
  - jika ingin Mengganti nama file db.json disesuikan di package.json pada *start: "json-server -p 3001 -w db.json*
  - *3001* adalah port running react, karna saya akan menjalankan 2 project secara bersamaan client dan db backend maka setting port ke *3001* untuk Menghindari tabrakan ketika running local server.

  ```json
     {
        "name": "api",
        "version": "1.0.0",
        "description": "",
        "main": "index.js",
        "scripts": {
            "start": "json-server -p 3001 -w db.json"
        },
        "author": "",
        "license": "ISC",
        "dependencies": {
            "json-server": "^0.16.1"
        }
    }
  ```