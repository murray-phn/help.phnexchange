# Setup development environment

1. Download python
2. `pip install mkdocs`
3. `pip install mkdocs-material`

# Live preview

Run command:
`mkdocs serve`

# How to edit

1. Create or update the .md files within /src
2. Update the mkdocs.yml file (this is what defines the side menu)
3. Push your changes to the repository
4. The live site will update within 5 minutes after push

# How to release

1. Run command: `mkdocs build`
2. Copy the CNAME file into the /docs directory
3. Commit & push the github repository

# Resources

How the website is hosted:
- https://pages.github.com/

The design of the help centre:
- https://www.mkdocs.org/
- https://www.mkdocs.org/user-guide/configuration/
- https://github.com/squidfunk/mkdocs-material
