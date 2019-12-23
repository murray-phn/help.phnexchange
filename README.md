# phn-exchange-docs

 https://phn-exchange.readthedocs.io/en/latest/ 
 

## how to install

download python
`pip install mkdocs`

`pip install mkdocs-material`

see live preview: `mkdocs serve`

## How to edit

1. Create/update your MD files
2. Update the mkdocs.yml file (this is what defines the side menu)
3. Push your changes to the repository
4. The live site will update within 5 minutes after push


## The plan

https://pages.github.com/

Host docs website as www.help.phnexchange.com.au

find a way to use the same box with a different service in the docker container

https://www.mkdocs.org/
https://github.com/squidfunk/mkdocs-material

make dockerfile with latest python:

apt-get update && upgrade

`pip install mkdocs`

`pip install mkdocs-material`

see live preview: `mkdocs serve`

install certbot & https on machine