# nck-metadata-file-microservice

 * **User Story:** : I can submit a FormData object that includes a file upload.
 * **User Story:** : When I submit something, I will receive the file size in bytes within the JSON response.

## Usage:

```
* upload a file
* response: {
  "status": 200,
  "filesize": 11901812
} 
```

### Installing and Running

To installing it on local dev env:

```
* install npm install
* run node server.js
```
## Built With

* [Node.js](https://nodejs.org/) - Execution environment
* [Express.js](http://expressjs.com/) - Web framework for Node.js programs
* [ejs](http://www.embeddedjs.com/) - Templating engine
* [multer](https://www.npmjs.com/package/multer) - Middleware for handling multipart/form-data


## Authors

* **Neckron**
