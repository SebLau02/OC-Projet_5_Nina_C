# To purge bootstrap:

    - cd to bootstrap folder and tap this command line
    - purgecss --css bootstrap.css --content "../../../**/*.html" "../../**/*.js" -o ../cleanStyle

# To purge style.css:

    - cd to assets and tap this command line

    - purgecss --css style.css --content "../**/*.html" "**/*.js" -o cleanStyle
