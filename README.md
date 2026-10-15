# Forelle
Welcome to version `1.0.0` of **Forelle** — a [GtkSourceView](https://gitlab.gnome.org/GNOME/gtksourceview) (GNOME-based) styling sheet!\
This style focusses on maintaining a warm palette, using a cream background, teal sidebar, and pink & green texts.\
\
This syling sheet is inspired off of SurrealEmber’s “Poisson 23” from the platform [Lospec](https://lospec.com/palette-list/poisson-23).\
Credit to him for this amazing palette!

# Compatabilities
Though Forelle works for all GtkSourceView-supportive applications, there are some which Forelle specifically targets. These include:
## LaTeX
Implemented from version `1.0.0`, Forelle supports LaTeX-specific highlighting!\
A screenshot of this in action can be seen below, using the LaTeX-editor *Gummi*.
<p align="center">
  <img src="images/TeX.png" alt="A screenshot of Gummi using the Forelle theme" width="750">
</p>

# How to Install
There are many sources you can find online to install xml files for GtkSourceView-supportive applications.\
As version 1.0 of Forelle was built with *Gummi* in mind, current install instructions are for *Gummi*.
## Gummi
Find your `gummi` directory, and locate the directory `gummi/styles/`.\
Then, copy or move the `forelle.xml` file from its original location to this directory.\
In Linux, this can be performed via running this command in Bash:
```
cp ~/Downloads/forelle.xml ~/.config/gummi/styles/
```
※ *note: your forelle.xml may be in a different location than Downloads—please write your command accordingly*

# Closing
This is all of Forelle for now! Any feedback is appreciated, and focussed compatability will expand for more GtkSourceView-supportive applications.\
Enjoy!
