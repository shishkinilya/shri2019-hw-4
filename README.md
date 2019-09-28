# Анализ сайта lifehacker.ru

## Вкладка Network

На вкладке network были обнаружены следующие недостатки:
1. Есть неминимизированные сss и js файлы, примеры:
![Unminimized css](https://raw.githubusercontent.com/shishkinilya/shri2019-hw-4/master/images/network/bbspoiler_css.png)
![Unminimized css](https://raw.githubusercontent.com/shishkinilya/shri2019-hw-4/master/images/network/style_css.png)
![Unminimized css](https://raw.githubusercontent.com/shishkinilya/shri2019-hw-4/master/images/network/widget_css.png)
2. Есть ресурсы с большим временем до первого байта, примеры:
![Long TTFB](https://raw.githubusercontent.com/shishkinilya/shri2019-hw-4/master/images/network/icomoon_ttfb.png)
![Long TTFB](https://raw.githubusercontent.com/shishkinilya/shri2019-hw-4/master/images/network/image_ttfb.png)
3. Не используется css свойство `font-display`, позволяющее 