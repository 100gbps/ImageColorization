# ImageColorization
Dependencies required -
* Torch7 (http://torch.ch/docs/getting-started.html)
* nn (Not really sure search for torch nn package might be included with tourch7) (https://github.com/torch/nn)
* image (luarocks install image)
* nngraph (Not really sure search for torch nn package might be included with tourch7) (https://github.com/torch/nngraph)

Once you install the above dependencies run the following command by placing the attached files in a particular project folder(it is just a regular folder).

th colorize.lua imageInput

Result- once you run the above command you get a colored image as file-out.png .If you want to name the output file run the command [ th colorize.lua imageInput outputName ] I have defined out.png as default output file name if no name is provided; this will prevent the perishing of old files by creating new output files everytime witth different names.
