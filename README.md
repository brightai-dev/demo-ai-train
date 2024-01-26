# demo-ai-train

Note: There are some issues with 3.12 python and pytorch.  For simplicity I went back to what we have previously used a lot 3.9

poetry env use 3.9
poetry install --no-root

To create this demo environment (you can do from scratch): this is what I did:
```
$ poetry add ultralytics
$ poetry add netron
$ poetry add -D jupyter 
$ poetry run jupyter notebook
```
.. and that's it, all the rest is in the notebook

