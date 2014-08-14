Readme: MNRAS Monthly Notices of the Royal Astronomical Society for Lyx

This is a LyX layout file and example Lyx document for the MNRAS mn2e.cls file. I haven't included mn2e.cls - you'll need to download it from:
http://www.wiley.com/bw/static/mnras_latex.asp

First off, a disclaimer: use this at your own risk; all copyright of the MNRAS is that of Wiley-Blackwell and the Monthly Notices (i.e. not me).

1. Put mn2e.cls in your latex class file directory, mn2e.bst in your latex bibtex directory. 
2. Put mn2e.layout in your lyx layout directory
3. Reconfigure latex 
4. Reconfigure LyX

And you should be all configured.

For example, for me on my mac (with mactex), I would run:

cp mn2e.cls ~/Library/texmf/tex/latex/
cp mn2e.bst ~/Library/texmf/bibtex/bst/
cp mn2e.layout ~/Library/Application\ Support/LyX-1.6/layouts/
sudo texhash

Then just open LyX, and run reconfigure from the menu. After that you should be good to go, so try opening mn2esample.lyx and making a PDF!

Good luck, I'll attempt to answer any emails, send 'em to:
danny.price@astro.ox.ac.uk
