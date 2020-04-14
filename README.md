# responxin
CSS definitions for Responsive Web Design using SASS.

This library is mainly composed of SASS mixins, using the syntax of SCSS.

Mixins are used to implement behaviour in different screen sizes.

Example:

```
@include if_screen3_small {
  #menuweb {display: none;}
  #barmenu {
    top: 0px;
  }
}
@include if_screen3_medium {
  #menuweb {display: none;}
  #barmenu {
    top: 0px;
  }
}
@include if_screen3_large {
  #menumovil {display: none;}
}
```

Mixins divide screen resolution in 3 or 4 sizes.

Mixins for 3 sizes are:

* if_screen3_small
* if_screen3_medium
* if_screen3_large

Mixins for 4 sizes are:

*if_screen4_tiny
*if_screen4_small
*if_screen4_medium
*if_screen4_large


