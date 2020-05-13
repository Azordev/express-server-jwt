<!-- PROJECT SHIELDS -->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues-open][issues-open-shield]][issues-url]
[![Issues-closed][issues-closed-shield]][issues-url]
[![Contributors][contributors-shield]][contributors-url]
[![Framework][badge-framework]][framework-url]
[![contributions welcome][contributions-welcome]][issues-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://">
	  <img src="https://img.icons8.com/color/96/000000/full-image.png" alt="Logo"/>
  </a>

  <h1 align="center">
	Express Server JWT
  </h1>

  <p align="center">
    A simple server with JWT authentication with the ability to create new users, and to authenticate the existing ones.
    <br />
	  🖊️
    <a href="https://">Read the article</a>
    🐞
    <a href="https://github.com/Israel-Laguan/express-server-jwt/issues">Report a Bug</a>
    🙋‍♂️
    <a href="https://github.com/Israel-Laguan/express-server-jwt/issues">Request Feature</a>
  </p>
</p>

## Table of Contents

1. [Endpoints](#endpoints)
2. [Get Started](#get-started)
3. [Author](#author)
4. [Contributing](#contributing)
5. [Show your support](#show-your-support)
6. [License](#license)

## Endpoints:
* /signin - POST (email, password)
* /signup - POST (email, password)
* /user - GET (protected)

## Get Started:

Download the repo and install all dependencies:
```
git clone https://github.com/alan2207/express-server-jwt
cd express-server-jwt
npm install
```

Configure the server:
```
touch config.js

# the configuration should look like this:
module.exports = {
  db: [your db url],
  port: [the port of the server],
  secret: [secret word for JWT]
};
```

Run the server:
```
npm start
```

# Author

<table style="width:100%">
  <tr>
    <td>
        <div align="center">
            <a href="./docs/img/photo.png" target="_blank" rel="author">
                <img src="https://avatars2.githubusercontent.com/u/36519478?s=460&v=4" style="border-radius: 10%; min-width: 100px;" alt="Israel Laguan's Photo" width="200px">
            </a>
            <h2>
                <a href="https://israel-laguan.github.io/" target="_blank" rel="author">
                    Israel Laguan
                </a>
            </h2>
        </div>
    </td>
    <td>
        <div align="center">
            <a href="mailto:israellaguan@gmail.com" target="_blank" rel="author">
                <img src="https://img.icons8.com/color/48/000000/message-squared.png" style="border-radius: 10%" alt="My GitHub" height="45px">
                <h3>
                    Email me to 
                    <a href="mailto:israellaguan@gmail.com">
                        israellaguan@gmail.com
                    </a>
                </h3>
            </a>
            <a href="https://www.linkedin.com/in/israellaguan/" target="_blank" rel="author">
                <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="My Linkedin" height="45px">
                <h3>
                    Connect to my Linkedin
                </h3>
            </a>
            <a href="https://github.com/Israel-Laguan" target="_blank" rel="author">
                <img src="https://img.icons8.com/color/48/000000/github--v1.png" 
			style="border-radius: 10%" alt="My GitHub" height="45px"
		>
                <h3>
                    Check my GitHub Profile
                </h3>
            </a>
        </div>
    </td>
  </tr>
</table> 

# Contributing

[![contributions welcome][contributions-welcome]][issues-url]

🤝 Contributions, issues and feature requests are welcome!
Feel free to check the [issues page][issues-url].

# Show your support

🤗 Give a ⭐️ if you like this project!

Icons from:

<a href="https://icons8.com/icon/13917/full-image">Icons8</a>

# License

[![License][badge-license]](http://badges.mit-license.org)

📝 This project is licensed under the [MIT](LICENSE)\
Feel free to fork this project and improve it

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/Israel-Laguan/express-server-jwt?style=for-the-badge
[contributors-url]: https://github.com/Israel-Laguan/express-server-jwt/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Israel-Laguan/express-server-jwt?style=for-the-badge
[forks-url]: https://github.com/Israel-Laguan/express-server-jwt/network/members
[stars-shield]: https://img.shields.io/github/stars/Israel-Laguan/express-server-jwt?style=for-the-badge
[stars-url]: https://github.com/Israel-Laguan/express-server-jwt/stargazers
[issues-open-shield]: https://img.shields.io/github/issues/Israel-Laguan/express-server-jwt?style=for-the-badge
[issues-url]: https://github.com/Israel-Laguan/express-server-jwt/issues
[issues-closed-shield]: https://img.shields.io/github/issues-closed/Israel-Laguan/express-server-jwt?style=for-the-badge
[badge-framework]: https://img.shields.io/badge/framework-here-9cf?style=for-the-badge
[framework-url]: https://google.com
[contributions-welcome]: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge
[badge-license]: https://img.shields.io/:license-mit-blue.svg?style=for-the-badge
