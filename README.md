# [![GitHub Header](https://raw.githubusercontent.com/leemcd56/leemcd56/main/assets/banner.png)](https://nathanael.rocks/)

<p align="center">
    <a href="https://dev.to/leemcd56">
        <img src="https://practicaldev-herokuapp-com.freetls.fastly.net/assets/rainbowdev.svg" alt="Nathanael McDaniel's DEV Community Profile" height="30" width="30">
    </a>
</p>

## About Me

```php
<?php

namespace Earth;

use Entities\Mammal\Human;

class Myself implements Human
{
    /**
     * Want to know where I work?
     *
     * @return array
     */
    public getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                [
                    'company' => 'Boone Software',
                    'position' => 'Partner',
                ],

                [
                    'company' => 'TopDevz',
                    'position' => 'Senior Software Engineer',
                ],
            ],
        ];
    }

    /**
     * These are the skills I use most often.
     *
     * @return array
     */
    public getSkills(): array
    {
        return [
            'JavaScript',
            'Laravel',
            'PHP',
            'PostgreSQL',
            'TypeScript',
            'Vue',
        ];
    }
}
```