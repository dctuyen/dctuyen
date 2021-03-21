<!--
**dctuyen/dctuyen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
![](https://komarev.com/ghpvc/?username=dctuyen&color=orange)
```php
<?php

namespace dinhCongTuyen;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'education' =>[
              'highSchool' => 'Xuan Truong B',
              'university' => 'Thuy Loi university',
            ]
            'workplace' => [
                'company' => null,
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Java::class,
            C#::class,
            C++::class,
            html,css,xml::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'to perfect my programming skills.';
    }
}
```
