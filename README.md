# Gitea-Red-Silver

Lite theme, yet not as much strain on the eyes as a bright or dark theme with red as main color.

## Directions

01. Find out where where your custom directory is (Site Administration, Configuration, Custom File Root Path)
02. Verify there is no public folder within the custom folder
03. If there is a public folder already there, make sure that both the css and img directories are created
04. If they do not exist, create them
05. To add just the theme and not use the red Gitea logos, copy theme-redsilver.css into the \path\to\custom\public\css folder
06. If you want to use the logos, make a backup of your existing img folder with `cp -a img img.bak`
07. Copy all of the logos from public/img into your img folder
08. Tell Gitea there is a new theme by editing or adding the app.ini file [ui] section:
```
[ui]
THEMES        = gitea,arc-green,redsilver
DEFAULT_THEME = redsilver
```

[![gitea-redsilver-01.png](https://pix.dou.bet/images/2020/09/22/gitea-redsilver-01.png)](https://pix.dou.bet/image/gKGN)
[![gitea-redsilver-02.png](https://pix.dou.bet/images/2020/09/22/gitea-redsilver-02.png)](https://pix.dou.bet/image/g2w7)
[![gitea-redsilver-03.png](https://pix.dou.bet/images/2020/09/22/gitea-redsilver-03.png)](https://pix.dou.bet/image/g4vn)
