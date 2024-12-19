# The No Bullshit Guide to Statistics
I made the repo noBSstats by Ivan Savov into a Mkdocs book.

[Original Repo Here](https://github.com/minireference/noBSstats)

1. I created the yaml file mkdocs.yml.

![image](https://github.com/user-attachments/assets/36c35ec8-11d3-4e2d-8a8a-63692c38c3c6)

2. I loaded the files from the repo into a docs/ file
3. Cloned the repo with GitHub cli
4. Created a remote git connection in the command line to the repo 

```git remote -v```

5. Set it to the right repository 

```git remote set-url origin git@github.com:<username/myrepo>.git```

6. Run the deployment command 

```python -m mkdocs gh-deploy -f <myrepo>/mkdocs.yml -v```

7. Set up github pages in settings to run off the new gh-pages


