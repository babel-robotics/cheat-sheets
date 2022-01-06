# Computer Modern Font

In order to use LaTeX Computer Modern fonts within Inkscape in Ubuntu 20.04 you can to 
install the font packages **_cm&#x2011;super_** and **_fonts&#x2011;cmu_** in the following order:

```
sudo apt-get install cm-super
```

```
sudo apt-get install fonts-cmu
```
  
Other options are [ctan.org](https://ctan.org/tex-archive/fonts/cm/ps-type1/bakoma/otf/) and [fontsquirrel.com](https://www.fontsquirrel.com/fonts/computer-modern). The former website provides many different LaTeX fonts in the OpenType format and on the latter you can download the Computer Modern CMU font from Donald E. Knuth in the **_.ttf_** fromat.

  
# Latin Modern Math Font
The Computer Modern Math font is available here [gust.org](http://www.gust.org.pl/projects/e-foundry/lm-math/download/index_html) as **_.otf_** files for use in any non-LaTeX programs supporting OpenType fonts.  
  
In Ubuntu 20.04 just copy the font file to a directory read by **font-config**. In most cases the directory **/usr/local/share/fonts** will be adequate (you can also copy the font file to ~/.fonts or /usr/share/fonts ).  
  
If the font doesn't appear in the applications font list you can run the **fc-cache** program in order to force a cache rebuild.  
  
# Re-editable LaTeX graphics

**TexText** is a Python extension for the vector graphics editor Inkscape providing the possibility to add and re-edit LaTeX generated SVG elements to your drawing

- [Installation](https://textext.github.io/textext/install/linux.html)
- [Documentation](https://textext.github.io/textext/usage/gui.html)
- [GitHub: textext](https://github.com/textext/textext)


# Converting PDF to SVG

A great guide to convert graphics from papers into SVG format via Inkscape is given on the blog from [danielherber.com](https://www.danielherber.com/guides.php?option=latex-inkscape).

# How to draw mathematical figures

Gilles Castel describes how he draw figures for his mathematical lecture notes using Inkscape on his blog [castel.dev](https://castel.dev/post/lecture-notes-2/).
  
He also nicely explains his workflow of taking notes with LateX and Vim here [lecture-notes-1](https://castel.dev/post/lecture-notes-1/), but this is not directly related to Inkscape anymore, so I will stop before straying from the topic of this cheat sheet.
