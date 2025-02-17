# dev-templates
A collection of development templates for starting projects and testing frameworks.


## How to use
Clone this repo:
```
git clone https://github.com/giper45/dev-templates
```
and copy the folder you are interested on.
Then, follow the `Configuration Guide` present in the template folder.


## General information
All the templates use `live-server` for static development: 
```
npm install -g live-server
```

All the templates have a `Makefile` that allows to execute the template with three basic command:
* `make install`: install the project dependencies.
* `make dev`:  run in dev mode
* `make run`: run the project with `live-server`

### Framework frontend
These are configuration that requires an installation with external dependencies, such as `angular`, `quasar`, `vuejs` ecc.

### Frontend vanilla 
In this folder, are present frameworks that does not contain external dependencies, just vanilla javascript and html.
For example: 
* bootstrap
* react


External `js` and `css` can be taken from `cdn` or installed locally.