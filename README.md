# no-mobile
Prevents image from showing in mobile view
Specifically used for additional images added to header

CSS
@media screen and (max-width: 800px) {
  #no-mobile {
    visibility: hidden;
    clear: both;
    float: left;
    margin: 10px auto 5px 20px;
    width: 28%;
    display: none;
  }
}

HTML example
<a href="{{ section.settings.logo-ad-link }}" itemprop="url" id="no-mobile">
