## Welcome to Experimentation

[Editor on GitHub](https://github.com/madhuri2k/experience-experiment/edit/gh-pages/README.md)

### Markdown reference
See [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll & Themes
[Jekyll](https://jekyllrb.com/) 
Change theme in repository settings.

# Github pages

[Github pages](https://pages.github.com) allows users to publish web-pages from their github content. There are two types of pages: 

1. User or organization site pages
   These are unique for every user (username.github.io) and published from a dedicated repository with the same name.
2. Project based site pages. Can be made from any repository owned by a user. Served at username.github.io/repo-name and the content is typically from a dedicated branch of the repo named `gh-pages`.

A website created via any of the above methods could be setup as an HTML-based website, in which case the repository directly contains the static HTML that is then served, or could be setup using markdown files which are automatically converted into HTML and served using jekyll.

While using jekyll there are 2 methods:
1. Use minima theme and let theme autogenerate the index.md (Best for blogs). In this case it's better to init the repo locally, and use `jekyll new` to create a skeleton and then push this to github.com.
2. Use any of the github-pages themes and create a hand-coded index markdown file (index.md or Readme.md). This is best for documenation sites and help sites where front-page doesn't change often.
   In this case, for testing web-site locally use `gem "github-pages" group: :jekyll_plugins` in Gemfile.
 
## Proposed Experiment
Try having index.md that has YAML Front-matter + some hand-coded markdown below and test switching between minima and pages themes and see if site works as expected in both cases (ignore irrelevant data in index). Also does any theme over-write the index.md making it unusable?

