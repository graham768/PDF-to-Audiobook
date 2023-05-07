# PDF to Audiobook

This notebook creates audio files for each chapter of a PDF book. You can take these chapter files to [AudioBookConverter](https://github.com/yermak/AudioBookConverter) or a similar platform to tie them all together into an m4b file that plays nicely with audio apps.

The example book isn't included for copyright concern. To split another book into chapters, add the pdf to the root directory, update the `book` variable and use the debugger cell to find unique details about your chapter titles. The script will then automatically split audio files when it finds these titles.

# Installation

`pip install -r requirements.txt`

To open the notebook, run `jupyter-lab` from the commandline and navigate to your notebook in the browser.