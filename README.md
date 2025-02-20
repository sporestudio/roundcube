<div align="center">
    <img src=".assets/logo.png" width=250px alt="rdlogo">
    <h1>ROUNDCUBE</h1>
</div>

Deployment of a Mail Server using Docker conatainers and Roundcube as mail interface.

## Features

- **DNS Server**: Dns service to resolve ftp address.
- **Roundcube Mail Server**: Web mail interface.

## Requirements

- **Unix-based system**.
- **Docker**.
- **Docker Compose**.
- **Valid Domain** to mail server.

## Deploy

#### Clone the repository

- First you have to clone this repo in your local machine.

```bash
$ git clone https://github.com/sporestudio/roundcube
$ cd roundcube/
```

#### Deploy the project

- Once we have our repo cloned, we can deploy the project using Docker Compose.

```bash
$ docker-compose up -d --build
```

## License

This project is under [MIT LICENSE](https://github.com/sporestudio/roundcube/blob/main/LICENSE).

## Author

This repository was created by [sporestudio](https://github.com/sporestudio).