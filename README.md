# 🍕 CIET - Can I Eat This? 🍲

CIET is an web app that translates and analyses the food ingredient by scanning the ingredient list on the food package, showing results of whether the food is compatible with their diet preferences. Currently only translating Japanese to English text is available with diet preferences for vegan, vegetarian, pescetarian, peanut-free and diary-free.

Link to the website! → https://www.ciet.lol

## Getting Started

### Setup

install gems

```bash
bundle install
```

###  ENV Variables

Create `.env` file

```bash
touch .env
```

Inside .env, set these variables and contact me if any API(s) and Access Token(s) is necessary!

```bash
CLOUDINARY_URL=your_own_cloudinary_url_key
DEEPL_AUTH_KEY=deepl_api_key
OPENAI_ACCESS_TOKEN=openai_access_token

```

### DB Setup

```bash
rails db:create
rails db:migrate
rails db:seed
```

### Run The Server

```bash
rails s
```
## Built With

* **Frontend** - HTML, [SCSS](https://sass-lang.com/guide/), [Bootstrap](https://getbootstrap.com/), [Stimulus JS](https://stimulus.hotwired.dev/)
* **Backend** - [Rails 7](https://guides.rubyonrails.org/)
* **Deployment** - [Namecheap](https://www.namecheap.com/)
* **Database** - [PostgreSQL](https://www.postgresql.org/)
* **Prototyping** - [Figma](https://www.figma.com/)

## Team Members

* [Felix Edgar Lange](https://github.com/flxlng)
* [Noah Taiga Endo](https://github.com/Octosub)
* [Leandro Munoz](https://github.com/leamuno)
* [Koji Mimura](https://github.com/imnadleeh)

## FAQ

Collaborations are welcome! Feel free to contact me or any other members for inquiries!

Rails app generated with lewagon/rails-templates, created by the Le Wagon coding bootcamp team.

README.md created using [README Creator](https://josuedla.github.io/readme-creator/) and [Editor.md](https://pandao.github.io/editor.md/en.html)
