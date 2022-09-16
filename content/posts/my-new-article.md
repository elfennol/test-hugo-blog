---
title: "My New Article"
date: 2022-09-08T11:43:29+02:00
lastmod: 2022-09-08T11:43:29+02:00
author: ["Elfennol"]
description: "My description"
categories: ["test"]
tags: ["php"]
draft: false
---

# My section

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce commodo dui quis laoreet varius. Nullam pretium euismod hendrerit. Aenean tempus, ipsum in tempus tempus, sapien ligula tristique velit, a scelerisque erat nunc eu leo. Aliquam rutrum mi in semper aliquet. Etiam dictum varius nibh, at feugiat eros cursus vitae. Mauris sit amet nisl sodales, feugiat est vitae, consectetur nulla. Duis hendrerit eros arcu, eleifend sodales diam tempus non.


Cras et justo fringilla erat scelerisque volutpat eget nec orci. Suspendisse vehicula vulputate volutpat. Mauris bibendum, quam quis aliquet finibus, tellus mauris vestibulum orci, id viverra diam turpis non libero. Suspendisse eget porta lectus, vel vulputate erat. Donec leo sem, tempor et rutrum nec, pharetra non libero. Duis finibus auctor velit id laoreet. Proin at scelerisque leo, ut ultricies lectus. In hac habitasse platea dictumst.

```php
namespace App\Controller;

use Symfony\Component\HttpFoundation\Response;

class LuckyController
{
    public function number(): Response
    {
        $number = random_int(0, 100);

        return new Response(
            '<html><body>Lucky number: '.$number.'</body></html>'
        );
    }
}
```

Vestibulum commodo eros eu facilisis consectetur. Donec commodo accumsan elit, a sagittis leo cursus vitae. Aenean imperdiet auctor justo. Phasellus a metus porttitor, suscipit mi in, vulputate risus. Pellentesque quis lorem neque. Duis in volutpat massa. Curabitur mattis, ipsum in sodales consectetur, leo diam auctor elit, nec aliquam tortor nisl viverra erat.



```js
fetch('http://example.com/movies.json')
  .then((response) => response.json())
  .then((data) => console.log(data));
```

---

**Discussions : https://github.com/elfennol/test-hugo-blog/discussions/8**