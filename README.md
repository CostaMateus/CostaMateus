```php
<?php

namespace MateusCosta;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'TDW Bi Consulting | Triibo',
                'position' => 'PHP Dev',
            ]
        ];
    }

    public function getKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Bootstrap::class,
            Javascript::class,
            Sql::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
