# lte-xataface
Theme for xataface based on AdminLTE ( https://github.com/almasaeed2010/AdminLTE )

## Installation:
1. Create folder "themes" in your xataface site directory.
2. Copy adminlte folder to new folder "themes".
3. In conf.ini add:
```
  [_themes]
  lte-xataface=themes/adminlte
```


You can add fontawesome icons ( http://fontawesome.io/icons/ ) to your menu. Add this new section to your conf.ini:
[_icons]
payment="fa-money"
links="fa-link"
menu="fa-navicon"

To load page without headers,left menu etc. you can add "load_ajax=1" or "iframe=1" GET paramaters to URL. Example: http://your_domain/admin/index.php?-table=user&iframe=1
