# Usage

Re-arrange svg / **cut out** part of the svg:  
1. ) select all   
2. ) use 'Object'>'Ungroup' (ctrl + u)  
3. ) freely move individual parts around  


# Computer Modern Font

In order to use LaTeX default fonts like Computer Modern within Inkscape you need to install the font packages **_cm&#x2011;super_** and **_fonts&#x2011;cmu_** in Ubuntu 20.04 with the following commands

```
sudo apt-get install cm-super
```

```
sudo apt-get install fonts-cmu
```
  
or add the fonts manually to a directory read by **font-config**. In Ubuntu 20.04 in most cases the directory **/usr/local/share/fonts** will be adequate (you can also copy the font file to ~/.fonts or /usr/share/fonts).  

If the font doesn't appear in the applications font list you can run the **fc-cache** program in order to force a cache rebuild.  

The website [ctan.org](https://ctan.org/tex-archive/fonts/cm/ps-type1/bakoma/otf/) provides many different LaTeX fonts in the OpenType format and on [fontsquirrel.com](https://www.fontsquirrel.com/fonts/computer-modern) you can download various Computer Modern CMU fonts from Donald E. Knuth in the **_.ttf_** format.  
  
The basic fonts are also stored locally in [../src/latex-fonts/](https://github.com/babel-robotics/cheatsheets/tree/main/src/latex-fonts)   
- [cmu10.otf](https://github.com/babel-robotics/cheatsheets/blob/main/src/latex-fonts/cmu10.otf) 
- [cmu-ttf](https://github.com/babel-robotics/cheatsheets/tree/main/src/latex-fonts/cmu-ttf) 
 
  
# Latin Modern Math Font
The Computer Modern Math font is available on [gust.org](http://www.gust.org.pl/projects/e-foundry/lm-math/download/index_html) as **_.otf_** files for use in any non-LaTeX programs supporting OpenType fonts or can be dwonloaded locally [latinmodern-math.otf](https://github.com/babel-robotics/cheatsheets/blob/main/src/latex-fonts/latinmodern-math.otf).
  
  
# Re-editable LaTeX graphics
**TexText** is a Python extension for the vector graphics editor Inkscape providing the possibility to add and re-edit LaTeX generated SVG elements to your drawing

- [Installation](https://textext.github.io/textext/install/linux.html)
- [Documentation](https://textext.github.io/textext/usage/gui.html)
- [GitHub: textext](https://github.com/textext/textext)


# Converting PDF to SVG

A great guide to convert graphics from scientific papers into SVG format via Inkscape is given on Daniel Herber's blog [danielherber.com](https://www.danielherber.com/guides.php?option=latex-inkscape).

# Computer Modern Font

In order to use LaTeX default fonts like Computer Modern within Inkscape you need to install the font packages **_cm&#x2011;super_** and **_fonts&#x2011;cmu_** in Ubuntu 20.04 with the following commands

```
sudo apt-get install cm-super
```

```
sudo apt-get install fonts-cmu
```
  
or add the fonts manually to a directory read by **font-config**. In Ubuntu 20.04 in most cases the directory **/usr/local/share/fonts** will be adequate (you can also copy the font file to ~/.fonts or /usr/share/fonts).  

If the font doesn't appear in the applications font list you can run the **fc-cache** program in order to force a cache rebuild.  

The website [ctan.org](https://ctan.org/tex-archive/fonts/cm/ps-type1/bakoma/otf/) provides many different LaTeX fonts in the OpenType format and on [fontsquirrel.com](https://www.fontsquirrel.com/fonts/computer-modern) you can download various Computer Modern CMU fonts from Donald E. Knuth in the **_.ttf_** format.  
  
The basic fonts are also stored locally in [../src/latex-fonts/](https://github.com/babel-robotics/cheatsheets/tree/main/src/latex-fonts)   
- [cmu10.otf](https://github.com/babel-robotics/cheatsheets/blob/main/src/latex-fonts/cmu10.otf) 
- [cmu-ttf](https://github.com/babel-robotics/cheatsheets/tree/main/src/latex-fonts/cmu-ttf) 
 
  
# Latin Modern Math Font
The Computer Modern Math font is available on [gust.org](http://www.gust.org.pl/projects/e-foundry/lm-math/download/index_html) as **_.otf_** files for use in any non-LaTeX programs supporting OpenType fonts or can be dwonloaded locally [latinmodern-math.otf](https://github.com/babel-robotics/cheatsheets/blob/main/src/latex-fonts/latinmodern-math.otf).
  
  
# Re-editable LaTeX graphics
**TexText** is a Python extension for the vector graphics editor Inkscape providing the possibility to add and re-edit LaTeX generated SVG elements to your drawing

- [Installation](https://textext.github.io/textext/install/linux.html)
- [Documentation](https://textext.github.io/textext/usage/gui.html)
- [GitHub: textext](https://github.com/textext/textext)


# Converting PDF to SVG

A great guide to convert graphics from scientific papers into SVG format via Inkscape is given on Daniel Herber's blog [danielherber.com](https://www.danielherber.com/guides.php?option=latex-inkscape).

# How to draw mathematical figures

Gilles Castel describes on his blog [castel.dev](https://castel.dev/post/lecture-notes-2/) how he draws figures for his mathematical lecture notes using Inkscape.
  
He also nicely explains his workflow of taking notes with LateX and Vim in this post [lecture-notes-1](https://castel.dev/post/lecture-notes-1/), but this is not directly related to Inkscape anymore, so I will stop before straying from the topic of this cheat sheet.
