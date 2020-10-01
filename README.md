<img src="https://miro.medium.com/max/2560/1*UBPbXxCACLSygvXutPPGSA.jpeg" alt="Github pages" />

# Github pages
Github pages is a simple way to deploy your static site or markdown text with github just using your github repository.

## How to use
If you want to host your project, it should be a static website like the one in this repo, made with only html, css and js for example, and should be pushed to the root of the repository.

To generate the github page you should create a branch named `gh-pages`. The project in this branch will be deployed by github automatically to *http://<username>.github.io/<repository>*.


Example of this repo: https://leonardozanotti.github.io/gh-pages/


If you project is pushed like my [Tour of Heroes project](https://github.com/LeonardoZanotti/Tour-of-Heroes), then you github page will load the markdown file.


Example of markdown file on github page: https://leonardozanotti.github.io/Tour-of-Heroes/

## Limits
* The hosted repository has 1GB limit;
* The hosted website has 1GB limit;
* Published websites by Github Pages has a band recommendation of 100GB or 100.000 (hundred thousand) requests per month;
* Published websites by Github Pages has a build limit of 10 builds per hour;
* If an user exceed this limits, the user will receive an email from GitHub (it is not very threatening, is it?)

## References
Thanks for Paula Grangeiro, for [his article](https://blog.paulagrangeiro.com.br/hospedando-sites-gratuitamente-com-o-github-pages-284aa643db14) about GitHub Pages.

## Leonardo Zanotti