
## Installation

### Prerequisites

* node
* npm
* mongodb

## Link to the deployed web app on Heroku

[https://reddit-backedn.herokuapp.com/](https://reddit-backedn.herokuapp.com/)

1. Clone this repository

2. Install server dependencies
    ```bash
    $ cd server
    $ npm ci
    ```
3. Install client dependencies
    ```bash
    $ cd client
    $ npm ci
    ```

## Run the app

1. Start mongodb locally
    ```bash
    $ mongod
    ```
2. Start the server
    ```bash
    $ cd server
    $ npm start
    ```
3. Start the client
    ```bash
    $ cd client
    $ npm start
    ```
4. Browse to `http://localhost:3000/`

## Testing

### Server
Make sure mongodb is running before testing the server.
```bash
$ cd server
$ npm test
```

### Client
```bash
$ cd client
$ npm test
```


Group Members
1. Brighton Mboya
2. Delyce Tuyezimana
3. Abraham Diress
4. Christian 
5. Lievin


