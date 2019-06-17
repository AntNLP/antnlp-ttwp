# A Template for Thesis Writing Projects (ECNU)

The repository contains a latex template for writing thesis (ECNU).

Run `xelatex main;bibtex main;xelatex main;xelatex main` to compile. 


## Requirements
+ latex software: texlive. Please compile with xelatex.
+ `STZhongsong.ttf` 

## FAQs

1. **The font `STZhongsong` cannot be found.**<br/></br>
`STZhongsong` is a commercial font, which you need to manually install first. 
One of the most convenient approach to get it is from Microsoft Word. 
For Mac users, you can find this font in /Applications/Microsoft Word.app/Contents/Resources/DFonts/STZHONGS.ttf. 
To install, you need to copy it into an Non-system path (e.g. ~/Desktop), then click to open and follow the instructions. 

2. **How can I change the type of the degree?(Ph.D. / Master)**<br/></br>
Change it in `committee.tex`, line 8 and `ecnu.sty` line 198.
