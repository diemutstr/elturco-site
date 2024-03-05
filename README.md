<p align="center">
  <a href="../../actions/workflows/deploy-gh-pages.yml">
    <img src="../../actions/workflows/deploy-gh-pages.yml/badge.svg" hspace="5"></a>
  <a href="../../actions/workflows/deploy-prod.yml">
    <img src="../../actions/workflows/deploy-prod.yml/badge.svg" hspace="5"></a>
</p>

---

# El-Turco Website

This repository has the source for the whole site. It also includes some scripts to generate images and various other things.

The relevant URLs for the contents is as follows:

* [`https://diemut.barzilay.org/`](https://diemut.barzilay.org/): Eli's playground.

  This usually has half-assed things which are used to debug new work.  **Do not share!**

* [`https://diemutstr.github.io/elturco-site/`](https://diemutstr.github.io/elturco-site/): GitHub pages.

  This is hosted on GitHub Pages, and it is updated automatically when new updates are added to the `main` branch.

  Can also be [triggered manually](https://github.com/diemutstr/elturco-site/actions/workflows/deploy-gh-pages.yml).

* [`https://elturco.diemutstrebe.com/`](https://elturco.diemutstrebe.com/): the actual site.

  Updated automatically whenever updates are pushed to the `prod` branch.

  Can also be [triggered manually](https://github.com/diemutstr/elturco-site/actions/workflows/deploy-prod.yml).

The two automated actions have their status badges at the top of this text.

***Add `/old` to any of the URLs to get the old site.***
