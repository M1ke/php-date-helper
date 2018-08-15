# PHP Date Helper
Provides quick date formatting key in CLI.

Install with composer, global is ideal:

```
composer global require m1ke/date-helper
```

It's useful to have your composer global bin directory in your `$PATH`; the directory is usually: `$HOME/.composer/vendor/bin/`

If you have it in your `$PATH` you can run this from any command line with `php-date-helper` and it will produce the following output:

```
d/j Date of month (with/out leading zeroes)
D/l Day text (short/long)
S   Suffix st,nd,rd,th
z   Day of year
F/M Month text (long/short)
m/n Month (with/out leading zeroes)
Y/y Year (4/2 digit)
a/A am or pm
h/g Hour (12hr, with/out leading zeroes)
H/G Hour (24hr, with/out leading zeries)
i   Minutes
s   Seconds
u   Microseconds
```

Contributions to add more dates or improve wording/formatting are welcome!

