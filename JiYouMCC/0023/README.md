第 0023 题： 使用 Python 的 Web 框架，做一个 Web 版本 留言簿 应用。
---------------------------------------

以前在sea上弄过一个差不多的：http://www.jithee.name/guestbook/
不过sea弄django syncdb比较痛苦，所有sql拼接出的
直接django真够傻瓜的……

代码版本用的sqlite3，本地调试的时候用的mysql

    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'guestbook',
        'USER': '',
        'PASSWORD': '',
        'HOST': '',
        'PORT': '',
    }
