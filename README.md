# Dev - Personal Portfolio

![GitHub repo size](https://img.shields.io/github/repo-size/ivansaul/personal-portfolio)
![GitHub stars](https://img.shields.io/github/stars/ivansaul/personal-portfolio)
![GitHub forks](https://img.shields.io/github/forks/ivansaul/personal-portfolio)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Dev-Portfolio is a fully responsive personal portfolio website, responsive for all devices, built using HTML, CSS, JavaScript and Python.

Live Preview: 👉🏽 [devfolio.githu.io](devfolio)

## Screenshots
![Desktop Demo](https://i.imgur.com/xKkMSwR.png "Desktop Demo")
![Mobile Demo](https://i.imgur.com/G1A1nBu.pngg "Mobile Demo")

## **How to make it yours?** 

### Step 1: 
Fork this project and rename the repo to `your_username.github.io`

### Step 2:
Go to the `config/` folder and replace the default data with your personal information.

```bash
config
|-- assets
|   |-- avatars
|   |-- icons
|   |-- posts
|   |-- projects
|-- about.toml
|-- blog.toml
|-- competencies.toml
|-- doing.toml
|-- projects.toml
|-- resume.toml
|-- social.toml
|-- technologies.toml
```

### Step 3:
Create a personal access token.

`Settings(Account) > Personal access tokens > tokens (classic) > Generate new token > Generate new token (classic) `

- [x] Expiration: No expiration

### Step 4: 
In the repository, create a new secret with the name `TOKEN_GITHUB` and paste your personal token there.

`Settings(Repo) > Secrets and Variables > Actions > Repository secrets`

### Step 5: 
Enable read and write permissions on:

`Settings(Repo) > Actions > General > Workflow permissions > Read and write permissions > save`

### Step 6: 
Enable GitHub Pages on:

`Settings(Repo) > Pages > Branch > Master > /(root > save`

### Step 6: Enjoy 😉
Now you can visit your portfolio at `https://your_username.github.io`

Your personal portfolio will be built and updated automatically whenever any changes occur in the configuration files.
 
> If you like my work and want to show some ❤️, please consider giving a ⭐️ to this Repository.

## Contact
If you want to contact me you can reach me at [Instagram](#).

## Credits
This project is based on [vcard portfolio](vard). The main focus of this project is adding new features and make it accessible to everyone.

## License

MIT

[vcard]: https://github.com/codewithsadee/vcard-personal-portfolio
[devfolio]: https://ivansaul.github.io/devfolio
