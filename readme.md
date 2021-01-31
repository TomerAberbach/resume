# Resume

> A LaTeX document for my resume.

[See it here!](https://github.com/TomerAberbach/resume/blob/main/resume.pdf)

## Installation

If you'd like to edit the resume in [Overleaf](https://overleaf.com), a zero setup online LaTeX editor with preview and real-time collaboration, then complete the following steps:

1. Fork the repository
2. If you don't have an Overleaf account, then [sign up](https://www.overleaf.com/register) for one
3. [Log into Overleaf](https://www.overleaf.com/login)
4. If your Overleaf account is not linked to your GitHub account, then go to the [account settings page](https://www.overleaf.com/user/settings), click on the "Link to your GitHub account" button, and follow the instructions to link your accounts
5. Go to your [Overleaf projects page](https://www.overleaf.com/project)
6. Click on the "New Project" button
7. Click on "Import from GitHub"
8. Click on the "Import to Overleaf" button adjacent to your fork of this repository
9. Wait for the repository to finish importing and for the LaTeX document to open. You will see compiler errors because the default compiler cannot compile this repository
10. Click on the "Menu" bottom at the top-left corner of the page and wait for a sidebar to open
11. In the "Settings" section of the newly opened sidebar, change the "Compiler" option to "XeLaTeX"
12. Click outside the sidebar to dismiss it, and click "Recompile" to see a preview of the resume!

If you'd like to edit the resume locally, then complete the following steps:
1. Clone the repository:

   ```sh
   $ git clone https://github.com/TomerAberbach/resume.git
   ```
2. Install [XeLaTeX](http://xetex.sourceforge.net) and run the appropriate command for your operating system to compile to PDF

## Usage

To edit the resume content without affecting the resume's layout, edit commands arguments in files under the [`content`](https://github.com/TomerAberbach/resume/tree/main/content) directory.

To hide, reorder, or create new sections, modify the lines under the `% Load Content` comment in [`main.tex`](https://github.com/TomerAberbach/resume/blob/main/main.tex) that correspond to the appropriate [`content`](https://github.com/TomerAberbach/resume/tree/main/content) directory file.

If you want to make more substantial changes, then search in [Overleaf's tutorials](https://www.overleaf.com/learn/latex/Tutorials). If you can't figure something out and need some help, then feel free to [file an issue](https://github.com/TomerAberbach/resume/issues/new/choose).

## License

[MIT](https://github.com/TomerAberbach/resume/blob/main/license) © [Tomer Aberbach](https://github.com/TomerAberbach)
