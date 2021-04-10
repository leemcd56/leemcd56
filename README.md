# [![GitHub Header](https://raw.githubusercontent.com/leemcd56/leemcd56/main/assets/banner.png)](https://nathanael.rocks/)

<h4>

```php
<?php

namespace Earth;

class Myself implements Person {
    /**
     * Want to know where I work?
     *
     * @return array
     */
    public getCurrentWorkplace(): array {
        return [
            'workplace' => [
                [
                    'company' => 'Boone Software, LLC',
                    'position' => 'Partner',
                ],

                [
                    'company' => 'Vendorin',
                    'position' => 'Senior Systems Engineer',
                ],
            ],
        ];
    }

    /**
     * These are the skills I use most often.
     *
     * @return array
     */
    public getSkills(): array {
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

</h4>