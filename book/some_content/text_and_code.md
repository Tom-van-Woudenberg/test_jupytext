---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.16.6
kernelspec:
  display_name: base
  language: python
  name: python3
---

# Text and code with output

```{custom_download_link} text_and_code.md
:text: "myst:md"
```

This page has both a ipynb and md version. It's referenced to by the toc with a `.ipynb` so that the output is visible here too. A download link replacer thing is added with:

````
```{custom_download_link} text_and_code.md
:text: "myst:md"
```
````

Both the ipynb and md can be edited locally. When you try to commit, the files are synced so that you commit the combined version.

If you make a change online, the pre-commit.ci thingy syncs the changes too, although it seems it fails on the pre-commit.ci website itself and it gives a red cross

```{code-cell} ipython3
print('hello world 4')
```
