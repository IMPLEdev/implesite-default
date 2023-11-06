# About default snippets

## implepage_header

To include in a template, use: `{HTML:default_implepage_header:VAR1|VAR2}`

- `VAR1` - color of the navbar: default or inverse
- `VAR2` - color of the the shadow navbar: nothing, default or inverse

There is a snippet inside this snippet: `{HTML:implepage_header_menu_special}`. You can define it for your site to add additional elements to the menu like buttons:

    <li>
      <form action="/contact" method="get" style="padding-top:9px;">
        <button class="btn btn-danger btn-sm shadow-default xs-mar-l-sm hover-zoom-1-1x">
          <i class="fa fa-calendar"></i> Schedule a call
        </button>
      </form>
    </li>

## implepage_footer

To include in a template, use: `{HTML:default_implepage_header:VAR1|VAR2}`

- `VAR1` - color of the navbar: default or inverse
- `VAR2` - color of the the shadow navbar: nothing, default or inverse

Inside this snippet are:

`{SETUP:footer_logo}` - let's you define url to an image with a footer logo.

`{MENU:default_implepage_footer}` - a default menu from main level pages with optional icons. Check https://github.com/IMPLEdev/implesite-default/main/menu/implepage_footer

`{HTML:implepage_footer_menu_special}`. You can define it for your site to add additional elements to the menu like buttons:

    <li>
      <form action="/contact" method="get">
        <button class="btn btn-danger shadow-default hover-zoom-1-1x">
          <i class="fa fa-calendar"></i><span> Schedule a call</span></button>
        </form>
      </li>

or links not present in a main menu, like:

    <li>
      <a href="/instagram" class=" hover-zoom-1-1x">
        <i class="fa fa-instagram text-danger"></i>
        <span class="hidden-xs"> Instagram</span>
      </a>
    </li>

you can also modify 



<li><form action="/kontakt" method="get"><button class="btn btn-danger shadow-default hover-zoom-1-1x" data-toggle="modal" data-target="#umowWizyte"><i class="fa fa-calendar"></i><span> Umów wizytę</span></button></form></li>
