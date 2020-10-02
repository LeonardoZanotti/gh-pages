<img src="https://miro.medium.com/max/2560/1*UBPbXxCACLSygvXutPPGSA.jpeg" alt="Github pages" />

# Github pages
Github pages are a simple way to deploy your static site or markdown text with github using only your github repository.

## How to use
If you want to host your project, it should be a static website like the one in this repo, made only with html, css and js for example, and should be pushed to the root of the repository.

To generate the github page you should create a branch named `gh-pages`. The project in this branch will be deployed by github automatically to **http://username.github.io/repository**.


Example of this repo: https://leonardozanotti.github.io/gh-pages/


If you project is pushed like my [Tour of Heroes project](https://github.com/LeonardoZanotti/Tour-of-Heroes), then you github page will load only the markdown file.


Example of markdown file on github page: https://leonardozanotti.github.io/Tour-of-Heroes/

## Limits
* The hosted repository has 1GB limit;
* The hosted website has 1GB limit;
* Published websites by Github Pages has a band recommendation of 100GB or 100.000 (hundred thousand) requests per month;
* Published websites by Github Pages has a build limit of 10 builds per hour;
* If an user exceed this limits, the user will receive an email from GitHub (it is not very threatening, is it?)


## Other option - Vercel
If you, for some reason, don't want to use Github pages, you can also use (Vercel)[https://vercel.com/] to deploy you static website with serverless functions.


It can deploy for 30+ Jamstack frameworks like React, Vuejs, Angular, Nuxtjs, Nextjs, etc. Works with 4.5B requests per week, 9PB data served and 99.99% guaranteed uptime.


To deploy on Vercel, you just need to connect your Github/Gitlab/Bitbucket account, select the repository and its done, very simple. I took about one minute to deploy my angular [Tour of Heroes project](https://github.com/LeonardoZanotti/Tour-of-Heroes) to Vercel in this [link](https://tour-of-heroes-bice.vercel.app/).

## References
Thanks for Paula Grangeiro, for [his article](https://blog.paulagrangeiro.com.br/hospedando-sites-gratuitamente-com-o-github-pages-284aa643db14) about GitHub Pages.

## Leonardo Zanotti