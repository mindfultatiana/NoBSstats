# The No Bullshit Guide to Statistics
I made the repo noBSstats by Ivan Savov into a Mkdocs book.

1. I created the yaml file mkdocs.yml.
2. I loaded the files from the repo into a docs/ file
3. Cloned the repo with GitHub cli
4. Created a remote git connection in the command line to the repo 

```git remote -v```

5. Set it to the right repository 

```git remote set-url origin git@github.com:mindfultatiana/NoBSstats.git```

6. Run the deployment command 

```python -m mkdocs gh-deploy -f NoBSstats/mkdocs.yml -v```

7. Set up github pages in settings to run off the new gh-pages


