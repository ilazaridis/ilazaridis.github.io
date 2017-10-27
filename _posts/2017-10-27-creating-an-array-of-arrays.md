---
excerpt: Useful tip to create an array of arrays
  
categories:
  - php
---

It's something already [officially documented](http://php.net/manual/en/function.array-map.php#example-5621)
but usually overlooked that's why I put it here for anyone including me ;).

```php
$a = [1, 2, 3, 4, 5];
$b = ['one', 'two', 'three', 'four', 'five'];
$c = ['uno', 'dos', 'tres', 'cuatro', 'cinco'];

$d = array_map(null, $a, $b, $c);
print_r($d);
```

[https://3v4l.org/0oQhS](https://3v4l.org/0oQhS)
