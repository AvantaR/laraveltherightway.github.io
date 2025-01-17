---
title:   Ekosystem
isChild: true
anchor:  the-ecosystem
---

## Ekosystem {#the_ecosystem}

Co najmniej musisz wiedzieć jak korzystać z [Gita](https://git-scm.com/){:target="_blank"} oraz [Composera](https://getcomposer.org/){:target="_blank"}. Mimo, że nie jest to wymagane, najlepiej jakbyś posiadał konto na [GitHub.com](https://github.com/){:target="_blank"}, ponieważ hostowany jest tam cały kod i wiele jego zależności.

MUSISZ czuć się swobodnie używając [wiersza poleceń (CLI)](https://pl.wikipedia.org/wiki/Wiersz_poleceń){:target="_blank"}, szczególnie powłok UNIXowych (sh, ksh, csh, tcsh, bash etc), gdyż są one często używane w trakcie pracy z Laravelem.

Pracując lokalnie, będziesz musiał zainstalować co najmniej [Vagranta](https://www.vagrantup.com/){:target="_blank"} i [VirtualBoxa](https://www.virtualbox.org/){:target="_blank"}. Są one używane przez [Homestead](https://laravel.com/docs/5.8/homestead){:target="_blank"} (specjalny Vagrantowy box przeznaczony do uruchamiania aplikacji Laravelowy). Możesz używać również tradycyjnych stacków takich jak WAMP/MAMP/XAMPP. Nie są one jednak oficjalne wspierane, możesz więc napotkać na różnego rodzaju problemy.

Pure “Laravel-way” frontend development might be a daunting one as it got has a long chain of technologies. You can either use [Laravel Blade](https://laravel.com/docs/5.8/blade){:target="_blank"} which is server-side templating or do client-side (browser), which at the very top of the chain is [Mix](https://laravel.com/docs/5.8/mix){:target="_blank"}, a wrapper for [Webpack](https://webpack.js.org/){:target="_blank"}. Webpack has its dependencies managed through [npm](https://www.npmjs.com/), all of which are packages of [NodeJS](https://nodejs.org/en/){:target="_blank"}.

CSS is managed either through [Sass](http://sass-lang.com/){:target="_blank"} or [LESS](http://lesscss.org/){:target="_blank"}, while JavaScript can be done through Plain JavaScript, [ReactJS](https://reactjs.org/){:target="_blank"} and the more common frontend framework used with Laravel: [VueJS](https://vuejs.org/){:target="_blank"}.

For the backend stack, at the very least, you need a web server like [Nginx](http://nginx.org/){:target="_blank"}, a php interpreter like [PHP-FPM](http://php-fpm.org/){:target="_blank"} and a database like [MySQL](https://www.mysql.com/){:target="_blank"}. Other optional stack components are [Memcached](http://memcached.org/){:target="_blank"}, [Redis](http://redis.io/){:target="_blank"} and [Beanstalkd](http://kr.github.io/beanstalkd/){:target="_blank"}.

While you are not required to understand them all at once, it is advantagous that you are at least familiar with these and do some reading about what they are and where they are being used. This will save you tons of confusion when reading the documentation and references in the future.
