# hexo-next-box
Hexo site with Next as the theme, out of the box and can be easily deployed on Vercel.
## version
> hexo 5.3.0<br>
hexo-theme-next 8.5.0
## feature
- site settings
    - Use Next as the default theme.
    - Add Tags, Categories and About pages by default.
    - Zh_cn as the default language.[Choosing Language](https://theme-next.js.org/docs/theme-settings/internationalization#Choosing-Language)
    - Word count and reading time.
- Enabled Third Party Services.
    - [local search](https://theme-next.js.org/docs/third-party-services/search-services.html#Local-Search)
    - [hexo-abbrlink](https://github.com/rozbo/hexo-abbrlink)
    - [hexo-excerpt](https://github.com/chekun/hexo-excerpt)
    - [hexo-related-popular-posts](https://github.com/tea3/hexo-related-popular-posts)
- Enabled Tag Plugins
    - [Note tag](https://theme-next.js.org/docs/tag-plugins/note.html)
    - [tabs tag](https://theme-next.js.org/docs/tag-plugins/tabs.html)
    - [hexo-github repo-tag](https://github.com/JoJoJotarou/hexo-github-repo-tag)
    - [hexo-tag-hint](https://github.com/etigerstudio/hexo-tag-hint)

## usage
- fork this repository
- update site info
    ```yaml
    # ~/_config.yml
    title: JoJoJotarou's Blog
    author: JoJoJotarou
    ```
- [Configuring Avatar](https://theme-next.js.org/docs/theme-settings/sidebar.html#Configuring-Avatar)
- add social accounts
    ```yaml
    #  theme/next/_config.yml
    social:
        GitHub: https://github.com/username || fab fa-github
        #E-Mail: mailto:yourname@gmail.com || fa fa-envelope
        #Weibo: https://weibo.com/yourname || fab fa-weibo
        #Google: https://plus.google.com/yourname || fab fa-google
        #Twitter: https://twitter.com/yourname || fab fa-twitter
        #FB Page: https://www.facebook.com/yourname || fab fa-facebook
        #StackOverflow: https://stackoverflow.com/yourname || fab fa-stack-overflow
        #YouTube: https://youtube.com/yourname || fab fa-youtube
        #Instagram: https://instagram.com/yourname || fab fa-instagram
        #Skype: skype:yourname?call|chat || fab fa-skype
    ```
- update github banner info
    ```yaml
    github_banner:
        permalink: https://github.com/username
    ```
- add more as you like
- deploy on [Vercel](https://vercel.com/) or other
