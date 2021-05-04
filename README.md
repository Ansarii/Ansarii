![Quote](https://github-readme-quotes.herokuapp.com/quote?theme=slateorange&animation=grow_out_in&layout=zues&font=Redressed)

```php
<?php

namespace Mohiuddin Ansari;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Emirates Auction',
                'position' => 'Android Developer'
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Java::class,
            Dart::class,
            Kotlin::class,
            Firebase::class,
            Angular::class,
            ReactNative::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
