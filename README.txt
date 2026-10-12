RITS consultation deck

The Role of RITS in Supporting Settlement in a Tokenised Ecosystem

Contents

rits-consultation-deck.tex  The editable source, copied without changes.
fonts/                    Fonts used by the source.
figures/                  Images used by the source.
RITS_Consultation.pdf      The supplied 77-page reference PDF.

Compile

Extract the whole ZIP. Keep the fonts and figures folders beside the TeX file.

Mac: install MacTeX and open the TeX file in TeXShop.
https://tug.org/mactex/mactex-download.html

Windows: install MiKTeX and open the TeX file in TeXworks. Allow MiKTeX to
install missing packages when prompted.
https://miktex.org/howto/install-miktex

Linux: install TeX Live with the full installation.
https://tug.org/texlive/quickinstall.html

Select XeLaTeX in your editor and typeset twice. The PDF produced is named
rits-consultation-deck.pdf. It should contain 77 pages.

Alternatively, open a terminal in this folder and run:

xelatex -halt-on-error rits-consultation-deck.tex
xelatex -halt-on-error rits-consultation-deck.tex

Use XeLaTeX because the source uses fontspec and bundled font files.

The hosted reference deck and downloads:
https://gerardjk.github.io/rits-consultation/

Related RITS visualisation:
https://www.rtgs.cash/
