# Latex_Templates

This project was created with the intention of provide some basic Latex Templates for creating documents. This templates can be drop at the texstudio templates folders. 
The JSON files contains the author information of said templates

## How to set up
This settings is for configure [TeXstudio](https://www.texstudio.org/)
*You can always use this templates in any other LaTeX enviroment*

### Windows

  1. Go to C:\Users\UserName\AppData\Roaming\texstudio\templates\user
  2. Copy-Paste the templates file .tex & .json
  3. Open TeXstudio
  4. Click on File --> New From Template ...
  5. Select the template you want under user

### Fedora Budgie Atomic
  1. Make sure you have installed a latex compilator like texlive
  2. Make sure the Commands on settings is well set up
     2.1.  "/var/usrlocal/texlive/2024/bin/x86_64-linux/pdflatex" -synctex=1 -interaction=nonstopmode %.tex
  3. Go to /home/userName/.var/app/org.texstudio.TeXstudio/config/texstudio/templates/user
