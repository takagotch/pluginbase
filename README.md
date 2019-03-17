### pluginbase
---
https://github.com/mitsuhiko/pluginbase

```py
from pluginbase import PluginBase
plugin_base = PluginBase(packae='yourapplication.plugins')

plugin_source = plugin_base.make_plugin_source(
  searchpath=['./path/to/plugings', './path/to/more/plugins'])

with plugin_source:
  from yourapplication.plugins import my_plugin
my_plugin.do_something_cool()

my_plugin = plugin_source.load_plugin('my_plugin')
my_plugin.do_something_cool()
```

```
```

```
```


