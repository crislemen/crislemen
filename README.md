```php
<?php

namespace Cristian León Méndez;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Cucunver',
                'position' => 'Full-Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            ReactJS::class,
            Angular::class,
            TailwindCss::class,
        ];
    }
    public function getLatestsWorkplaces(): array
    {
        return [
            'workplaces' => [{
                'company' => 'Elliot-Cloud',
                'position' => 'Front-End Developer'         
            },
            {
                'company' => 'Bosonit',
                'position' => 'Front-End Developer'         
            },
            {
                'company' => 'E-asy',
                'position' => 'Front-End Developer'
            }];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source and being good developer.';
    }
}
```
