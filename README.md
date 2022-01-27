 https-trofyna.github.io-goit-markup-hw-07-bem


<!-- Structure for BEM -->

<!-- 
BLOCK 1 page-header
BLOCK 2  container
BLOCK 3 site-nav (old - не было class)
--------------------Это и есть МИКС.------------------
--В этом месте блок logo стал ещё и элементом  BLOCK 3 site-nav----
  BLOCK 4.0  logo
        ELEM 4__1  logo__text  
             MODIFICATOR  4__1--1   logo__text--black
                            (old:logo-color-black)
             MODIFICATOR  4__1--2    logo__text--white   
                            (old:logo-color-white)
    ELEM 3__1  site-nav__links
                (old:links)
    ELEM 3__2   site-nav__item
             MODIFICATOR  3__2--1   site-nav__item--active
                (old:link-nav-index) in PORTF: link-nav
    ELEM 3__3   site-nav__item
            MODIFICATOR  3__3--1   site-nav__item--active
                (old:link-nav) in PORTF:  link-nav-portfolio
    ELEM 3__4   site-nav__item
                (old:link-nav)


BLOCK 5 auth-nav 
    (old:contacts)
    ELEM 5__1  auth-nav__links
                (old:a-mail)
    ELEM 5__2   auth-nav__img
             (old:icon-envelopehover-svg)
    ELEM 5__3  auth-nav__links
                (old:a-mail)
    ELEM 5__4   auth-nav__img
             (old:icon-mobile-svg)

BLOCK 6 hero
    ELEM 6__1  hero__title
                (hero-title)





 -->


