# To Do

* look at the free version of https://deviceatlas.com/pricing?form=cloud-free
  * see https://mobiforge.com/design-development/javascript-server-side-rendering-with-device-detection

* improve design
  * highlight the url on the host page
  * get a color scheme

* automate https certificate renewal

* build out account features to remember previous UAs
  * allow account creation
    * use bcrypt
    * consider allowing oauth (optional)
  * allow logging in
  * remember logged-in status in a cookie (optional, but desired)
  * allow url customization
  * identify custom URLs
    * different prefix vs anon's
    * no prefix - check performance impact, consider preloading list into mem
  * on custom hit, store in db (probably as a new doc)

* offer free open-source accounts

* charge money for pro & business accounts

* look into https://github.com/googleanalytics/autotrack#loading-autotrack-via-npm

* figure out how to make antifreeze work

* get useragent.io
  * make https work there

* blog
