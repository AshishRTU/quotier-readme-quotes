<div align="center"> 
 <h1> QUOTIER </h1>
 <img src="https://img.shields.io/github/package-json/v/GDSC-RTU/quotier-readme-quotes?color=g&label=QUOTIER">
 <img src="https://img.shields.io/npm/v/npm">
 <img src="https://img.shields.io/github/languages/code-size/GDSC-RTU/quotier-readme-quotes?logo=github">
</div>

## Use

API for Quotes📑 in JSON and rendered SVG form - Use it anywhere on GitHub, Your Website or wherever you like✨

## How to use

In your GitHub readme

```markdown
![QUOTES](https://quotier.vercel.app/quote)
```

In html

```html
<img src="https://quotier.vercel.app/quote" alt="Quotes" />
```

## Endpoints

- / => Will return basic Hello Page in API
- /quote => Will return a random quote in rendered SVG form

## Run the application locally

- Make sure you have NodeJS installed. Check it by typing this command in your terminal -

```
node --version
```

- Fork this repository.

- Clone this repository by running the following command in your terminal -

```
git clone https://github.com/GDSC-RTU/quotier-readme-quote
```

- cd into the folder by using the following command -

```
cd quotier-readme-quote
```

- Install the dependencies by running the following command -

```
npm install
```

- Setting Up development Enviornment create a `.env` file in root folver and add the following line

```env
NODE_ENV = development
```

- To run the application, type the following command in your terminal -

```
npm run develop
```

- Access the results produced by accessing the following URL in your browser -

```
localhost:3000
```

## Contribution Guidelines

Check [contribution.md](Contributing.md) if you want to learn how to make a contribution.

Append your quote to quote.json inside the quote/ folder and raise the PR.

```
{
    "quote":"Your new Quote",
    "author":"Author of your quote",
}
```

### Note :

- Please avoid the repetition of quotes.
- Do not make any changes in other files.
