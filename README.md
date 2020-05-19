<h1 align="center">
  <br>
  <img src="https://miro.medium.com/max/661/1*TkP2EwaX95ItAv_jGS7hSA.png" width="400">
  <br>
  Lalavent - Backend
  <br>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/ExpressJs-v4.17.1-yellow">
  <img src="https://img.shields.io/badge/Axios-v0.19.2-blue">
  <img src="https://img.shields.io/badge/Sequelize-v5.21.6-important">
  <img src="https://img.shields.io/badge/Nodemailer-v6.4.6-red">
</p>

## Table of Contents
- [Prerequiste](#prerequiste)
- [Installation](#installation)
- [Contributing](#contributing)
- [Related Project](#related-project)
- [Contributors](#contributors)

## Prerequiste
- Node.js - Download and Install [Node.js](https://nodejs.org/en/).
- MySQL - Download and Install [MySQL](https://www.mysql.com/downloads/) - Make sure it's running on the default port.
- Sequelize - Download and Install [Sequelize](https://sequelize.org/)

## Installation
### Clone
```
$ git clone https://github.com/shoelfikar/lalavent.server.git
$ cd lalavent.server
$ npm install
```

### Create Environment Variable
```
$ touch .env
$ nano .env
```

```
DB_HOST="Your_Host"
DB_USER="Your_Username"
DB_PASSWORD="Your_Password"
DB_NAME="Your_Table"

SERVER_PORT="Your_Port"

```

### Start Development Server
```
$ npm start
```
## Link Collection Postman
[Postman](https://www.getpostman.com/collections/a393e0f1a889241cd194)

## Structure Folder
```
\---src
|    \---controller
|    |   +---category.js
|    |   +---event.js
|    |   +---role.js
|    |   +---ticket.js
|    |   +---user.js
|    \---helper
|    |   +---error.js
|    |   +---sendmail.js
|    |   +---upload.js
|    \---models
|    |   +---category.js
|    |   +---event.js
|    |   +---index.js
|    |   +---role.js
|    |   +---ticket.js
|    |   +---user.js
|    \---router
|    |   +---category.js
|    |   +---event.js
|    |   +---role.js
|    |   +---ticket.js
|    |   +---user.js
+---app.js
+---server.js
```


## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project
1. Create your Feature Branch  ```git checkout -b [feature]```
2. Commit your Changes ```git commit -m 'Add some feature'```
3. Push to the Branch ```git push origin [feature]```
4. Open a Pull Request

## Related Project
* [`Lalaventt-Frontend-VueJs`](https://github.com/ichvanul/lalavent.client.git)

## Contributors

<center>
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/ichvanul">
          <img width="150" src="https://avatars1.githubusercontent.com/u/62008205?s=460&u=d23a93172c5e4c40b9b033e273a3359b2742c568&v=4" alt="Ichvanul Yulizar Putra"><br/>
          <b>Ichvanul Yulizar Putra</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/algol007">
          <img width="150" src="https://avatars3.githubusercontent.com/u/13137672?s=460&u=b5226ccdf4cd9c9a8505215b77b2a15d134d92b5&v=4" alt="Ady Rahmansyah"><br/>
          <b>Ady Rahmansyah</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/fblazt">
          <img width="150" src="https://avatars3.githubusercontent.com/u/48191467?s=460&u=c06616d146930100dfb5eb5c4ab10fd00d01ac41&v=4" alt="Firman"><br/>
          <b>Firman</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/shoelfikar">
          <img width="150" src="https://avatars2.githubusercontent.com/u/55390061?s=400&u=74904e4071d513890cfd34031b87977eeddb09b8&v=4" alt="Sulfikardi"><br/>
          <b>Sulfikardi</b>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/slucter">
          <img width="150" src="https://avatars2.githubusercontent.com/u/61655908?s=460&u=1e1c0b55b30cf502f264038f39609fd6dc8636b8&v=4" alt="Muhamad Irhashdianto"><br/>
          <b>Muhamad Irhashdianto</b>
        </a>
      </td>
    </tr>
  </table>
</center>

