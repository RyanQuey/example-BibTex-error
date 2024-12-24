Sample latex project to quickly show where errors are happening. 
- Useful for sharing code, to post in SO
- Useful for debugging also. Makes things simple. 

# Edit

- Vim works great, there's a plugin to get LaTex support for color etc
- VS Code is also a good option

# Build
## Vim
Using setup as of Nov 2024:
1) Open .tex file in vim

2) Start auto-compiling using TexVim: \ll
- It will take a while for large files to compile, so just sit and wait.
- Eventually it should open up your PDF reader and the generated PDF file. 
- Note that if it TOTALLY fails, it will just say it failed. 
    - Sometimes, that just means you need to try again (\ll and then \ll again)
- Note that if it builds with errors, it will show the PDF, but then list out
  the errors in the panel at the bottom of the vim window. 

4) Stop auto-compiling using TexVim: \ll

5) Clear build files using TexVim: \lc
