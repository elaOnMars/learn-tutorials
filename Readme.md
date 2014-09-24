# Plotly learn tutorials

*Welcome the to Plotly learn tutorials repository!*

### Goals of this repo

Make updating, adding content to and fixing typos in
[plot.ly](https://plot/ly/learn)
learn tutorials fast and easy, for all!

Make contents in goggle documents
([examples](https://drive.google.com/a/plot.ly/#folders/0B2KhXoOOCkxHdmpmdkNpNEE5WEU)) 
one command away from being *plot.ly-ready*.

### Files and folders in this repo:

Scripts and commands:

- `_scripts/` : scripts handling the conversion to *plot.ly-ready* process
- `makefile/` : shortcut commands to run the scripts, show conversion log and
  push the published content to the `streambed/` repository (more in
  [`Contributing.md`](./Contributing.md))

Content directory:

- `web_app_tutorials/` : content of the web app tutorials 
  ([example](https://plot.ly/how-to-make-a-bar-chart-online/))
- `excel_tutorials/` : content of the excel tutorials
  ([example](https://plot.ly/how-to-make-an-area-chart-with-excel/))
- `data_literacy/` : content of the data literacy tutorials 
  ([example](https://plot.ly/box-plot/))

Each content directory contains:

- `raw/` subdirectory : content (HTML files etc) from imported google documents
- `published/` subdirectory : content generated by the scripts
- `translate_static.json` file : rules for static references (e.g. images)
- `translate_filename_url.json` file : rules for naming urls

### Have tutorials to update, add or fix?

Please read [`Contributing.md`](./Contributing.md)
