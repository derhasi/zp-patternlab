# ZP Patternlab

Providing style patterns and kind of prototype for the Zugspitzpokal redesign by
implementing the [great Pattern Lab](http://patternlab.io/).

## Commands

To show the patternlab site, generate it ...

```
php patternlab-php/core/builder.php -g
```

... and open it in the browser ...

```
open patternlab-php/public/index.html
```

### Development

Watch patternlab changes
```
php patternlab-php/core/builder.php -w
```

Watch sass changes
```
compass watch source
```

Auto reload
```
php patternlab-php/core/autoReloadServer.php
```
