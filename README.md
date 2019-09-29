
# Resume
Resume with Jekill for Github pages.
<a href="https://cnrun.github.io/">cnrun.github.io</a>

# Build
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:3.8 jekyll build

# Visualise
docker run --name online-cv-nginx -v "$PWD/_site:/usr/share/nginx/html:ro" -d -p 8080:80 nginx
open <a href="http://localhost:8080">localhost:8080</a>

## Credits
Theme from by Xiaoying Riley at [3rd Wave Media](http://themes.3rdwavemedia.com/). Visit her [website](http://themes.3rdwavemedia.com/) for more themes.

Thanks to [Nelson Estevão](https://github.com/nelsonmestevao) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=nelsonmestevao).

Thanks to [t-h-e(sfrost)](https://github.com/t-h-e) for all the [contributions](https://github.com/sharu725/online-cv/commits?author=t-h-e).

Check out for more themes: [**Jekyll Themes**](http://jekyll-themes.com).

## License

This project is licensed under the [MIT license](LICENSE.txt).
