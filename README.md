# Simple environment plugin disabler for WordPress

Courtesy of [Kamil Grzegorczyk](https://kamilgrzegorczyk.com/2018/05/02/how-to-disable-plugins-on-certain-environment/) &  [Mark Jaquith](https://gist.github.com/markjaquith/1044546) 

## Usage

Install as `mu-plugin`.

Define your disabled plugins via

```
define('DEV_DISABLED_PLUGINS', serialize([
	'autoptimize/autoptimize.php',
	'wp-super-cache/wp-cache.php'
]));
```

See this [blog post](https://kamilgrzegorczyk.com/2018/05/02/how-to-disable-plugins-on-certain-environment/) for more information.