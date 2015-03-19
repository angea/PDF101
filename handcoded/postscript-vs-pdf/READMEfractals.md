# PDF and PostScript: Myths, Guesses and Facts

* PDF is not an "extension of PostScript" (PS is a Turing-complete programming language -- PDF is not!)    
  <sub>Yes, PDF inherited its basic graphics model from PS (and extended it with many new features) </sub>

* But PDF got everything removed what made PS a programming language: conditions, loops, arithmetics,... precisely because it did more bad than good for PS as: (1) a universal "electronic document format"; (2) a "reliable print job format"    
  <sub>(however, its retrofitted JavaScript support since PDF-1.3 makes up for this ;-) </sub>

* Which format does typically require smaller file sizes for identical screen or page content? PDF or PS?    
  <sub>(Make an un-educated guess, if you dare. Then look at the fractals-sierpinski-*.ps files. Open them in a text editor. Convert them to PDF with Ghostscript -- a working command is in the PS comments. Check their respective file sizes.)</sub>

* Which graphics type does typically produce smaller files for the same screen or page content? Raster images or vector drawings?    
  <sub>(Again, make an un-educated guess, if you dare. Then look at the same files as above. Open them in a text editor. Convert them to PDF with Ghostscript -- a working command is in the PS comments. Open them, one after another in your favorite PDF viewer and watch them render... Would the PS version render faster?)</sub>

