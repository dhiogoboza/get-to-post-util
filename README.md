# get-to-post-utils

Utility to send a `POST` method to an URL using `GET` params. This tool is useful for example in android applications intents to open a site with a `POST` result in browser.

## Usage

Send a `GET` request to `https://dhiogoboza.github.io/get-to-post-utils/topost.html` with your GET params and use `s` param to set the target URL:

- `s`: URL to send the post
- All remaining params will be sent in `POST` form data

## Example

https://dhiogoboza.github.io/get-to-post-utils/topost.html?s=https://www2.correios.com.br/sistemas/rastreamento/resultado.cfm&objetos=LO900248154CN&acao=track
