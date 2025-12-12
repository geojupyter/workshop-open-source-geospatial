::::::{hint} Joining late? You may need to clone the workshop repository
:class: dropdown

If you're joining late, you may have missed a prior instruction to start your CryoCloud server,
clone the workshop website and set up GitHub authentication.

To start your CryoCloud server, visit the reference section [](/reference/01-starting-your-server.md).

To clone the workshop repository, open a terminal in your CryoCloud JupyterLab server:

```bash
cd  # Move to your home directory
git clone https://github.com/geojupyter/workshop-open-source-geospatial.git
```

:::{youShouldNotice}
...this command produces output like:

```
Cloning into 'workshop-open-source-geospatial'...
remote: Enumerating objects: 417, done.
remote: Counting objects: 100% (178/178), done.
remote: Compressing objects: 100% (101/101), done.
remote: Total 417 (delta 136), reused 97 (delta 77), pack-reused 239 (from 2)
Receiving objects: 100% (417/417), 1.13 MiB | 7.21 MiB/s, done.
Resolving deltas: 100% (229/229), done.
```
:::

**Finally, you'll need to setup GitHub authentication to push to GitHub**, which is required to
complete some modules (e.g. module 5).
Please follow the instructions at [](/reference/03-gh-auth.md).
::::::
