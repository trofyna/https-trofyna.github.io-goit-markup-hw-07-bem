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
ELEM 5__2  auth-nav__img
               (old:icon-envelopehover-svg)
            MODIFICATOR  5__2--1             auth-nav__img--wider
ELEM 5__3  auth-nav__links
                (old:a-mail)
ELEM 5__4   auth-nav__img
             (old:icon-mobile-svg)
            MODIFICATOR  5__4--1             auth-nav__img--higher
    

BLOCK 6 hero
ELEM 6__1  hero__title
                (old:hero-title)
ELEM 6__2  hero__btn
                 (old:hero-btn)
BLOCK 7 backdrop is-hidden
BLOCK 8 modal
ELEM 8__1  modal__exit
                ( old:exit)
ELEM 8__2  modal__btn
                (old: btn-exit-modal)
ELEM 8__3  modal__img
                (old: close)
        
ELEM 8__4  modal__form
                 ( old: div> send-to-modal)
                
    BLOCK 9.0 form
                (old:modal-form;
                 js-contact-form;
                  js-speaker-formM)

ELEM 9__1  form__title
                   ( old: h3> send-to-modal)

3 TIMES (Имя,Телефон,Почта)
        ELEM 9__2  form__field
                   ( old:> label-style-modal)
        ELEM 9__3  form__label
                   ( old:> span-style-modal)
        ELEM 9__4  form__input
                    ( old:> input-style-modal)
        ELEM 9__5  form__img (vector)
                   ( old:>icon-svg-modal)

1 TIMES (Комментарий)
         ELEM 9__6  form__field
                   ( old:> label-style-modal)
        ELEM 9__7  form__label
                   ( old:> span-style-modal)
        ELEM 9__8  form__text
                   ( old:>fback)

1 TIMES (checkbox)
ELEM 9__6  form__field
                MODIFICATOR  9__6--1        form__field--check
                   ( old:> label-style-check)
ELEM 9__7  form__input
                MODIFICATOR  9__7--1
                form__input--check     
                   ( old:>checkbox)
ELEM 9__8  form__img (vector)
                MODIFICATOR  9__8--1
                form__img (vector)--check
                   ( old:>icon-check)

1 TIMES (Условия)
ELEM 9__9  form__label
                 MODIFICATOR  9__9--1
                form__label--condition     
                  ( old:> span-style-modal-condi)
ELEM 9__10  form__link
                   ( old:>conditions)
ELEM 9__11  form__btn
                   ( old:>btn-sendup)
                   
BLOCK 10 section
ELEM 10__1  section__title
                   ( old:> hedden-elem )
               0.block-util  +  .hedden-elem
                 
BLOCK 11 container
            MODIFICATOR  11--1
                container--rght
                  ( old:> container advant)

BLOCK 12 advantages
            ( old:> ul>)

3 TIMES (icon-antenna,icon-clock,icon-diagram,icon-diagram )

ELEM 12__1  advantages__block
                   ( old:>li> list-advantages )
ELEM 12__2  advantages__item
                   ( old:> div> icon-antenna )
ELEM 12__3  advantages__image
                   ( old:> svg> icon-antenna-svg)
ELEM 12__4  advantages__title
                   ( old:> h3> advantages)
ELEM 12__5  advantages__text
                   ( old:> p> advantages-text)

BLOCK 13 section
            MODIFICATOR  13--1
                section--down
                  ( old:> section do)
ELEM 13__1  section__title
               MODIFICATOR  13__1--1 section__title--base
               (doing)
BLOCK 14 container
3 TIMES 
(Десктопные приложения,Мобильные приложения,Дизайнерские решения)
BLOCK 15 suggestion (list-image-do)
ELEM 15__1 suggestion__thumb (product-thumb)
ELEM 15__2 suggestion__image (image-do)
ELEM 15__3 suggestion__title (item-do)


BLOCK 16 section
            MODIFICATOR  16--1
                section--bckgrnd
                  ( old:> section bgteam)
ELEM 16__1  section__title
               MODIFICATOR  16__1--1 section__title--base
               (team)
BLOCK 17 container (div>container)
BLOCK 18 team (ul> list-image-team)

4 times (Игорь,Ольга,Николай,Михаил,)
ELEM 18__1 team__image (li>card-point)
ELEM 18__2 team__block (div>card-team)
ELEM 18__3 team__title (h3>img-name)
ELEM 18__4 team__text (p>img-proff)
--------------------Это и есть МИКС.------------------
-В этом месте блок social стал ещё и элементом  BLOCK 18 team---
BLOCK 19.0  social (ul)
4 times (instagram,twitter,fb,linkedin,)
ELEM 19__1  social__point (li> social-link)
ELEM 19__2  social__link (а> btn-soc)
        for FOOTER MODIFICATOR  
        19__2--1 social__link--lghtbckgrnd ( а> btn-soc connect)

ELEM 19__3  social__img (> soc-icon-svg)


BLOCK 20  section
BLOCK 21  container
ELEM  21__1  section__title
               MODIFICATOR  16__1--1 section__title--base
               ( old:> regular clients)
BLOCK 22  clients (ul>)

6 times for logo from 1 to 6
BLOCK 23  clients__item (li> client)
BLOCK 24  clients__link (a> btn-client)
BLOCK 25  clients__image (svg> client-icon-svg)

BLOCK 26  page-footer
BLOCK 27  container
            MODIFICATOR  27--1 container--flex
               (div>container + div> logo-address-join-soc)

BLOCK 28  container

BLOCK 29  logo-address
BLOCK 30 logo as in header
    logo__text 
        logo__text--white
BLOCK 31 footer-contact  (ul>list-address)
31__1 elem  footer-contact__item
        modi footer-contact__item--white
31__2 elem  footer-contact__item (li>address-footer)
31__3 elem  footer-contact__item  (address-footer)

BLOCK 32  join  (join-colum)
elem32__1  join__title (join)

--------------------Это и есть МИКС.------------------
-В этом месте блок social стал ещё и элементом  BLOCK 18 team---
BLOCK 33 
like 19.0  social (ul)
4 times (instagram,twitter,fb,linkedin,)
ELEM 19__1  social__point (li> social-link)
ELEM 19__2  social__link (а> btn-soc)
        for FOOTER MODIFICATOR  
        19__2--1 social__link--lghtbckgrnd ( а> btn-soc connect)

ELEM 19__3  social__img (> soc-icon-svg)

BLOCK 34  sign-up div>
block  35 js-speaker-form form >


script modal
script current

block  36 section ( portfolio)
             modi  section--down
hedden-elem h1>
block 37 container div>
cblock 38 list-btn ul>
            list-btn__item  list-btn__item--shadow
            list-btn__item  list-btn__item--maincolor
            list-btn__item   list-btn__item--maincolor
            list-btn__item   list-btn__item--maincolor

cblock 39 portfolio-list ul>(container-main-por)
elem portfolio-list__item li>(card-portfolio)
            modi portfolio-list__item--one...
        ... modi portfolio-list__item--nine
elem portfolio-list__link a> 
img>       
elem portfolio-list__info div>>
elem portfolio-list__kryak div>
elem portfolio-list__title h2>
elem portfolio-list__text p>


 -->


