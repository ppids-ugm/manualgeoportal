just to note the ghp-import magic line:


sphinx-build -b html ./_src ./_build/html

sphinx-autobuild ./_src ./_build/html

ghp-import -n -p ./_build/html
