```php
<?php

namespace GitHub\SMhdHsn;

/**
 * @email <m2hdtl@gmail.com>
 * @location Tehran, Iran
 * @birth 1998-08-23
 */
class About extends Programming implements PSR, SOLID
{
    public function __construct()
    {
        echo 'Hi There!';
    }

    public function getCurrentWorkplace(): array
    {
        return [
            'current' => [
                'company' => 'Snappfood.ir',
                'position' => 'Back-End Developer',
            ],
            'recent' => [
                [
                    'company' => 'HiTrav.com',
                    'position' => 'Back-End Developer',         
                ],
            ],
        ];
    }

    public function getKnowledgeStack(): array
    {
        return [
            PHP::class,
            GO::class,

            Laravel::class,
            Symfony::class,

            MySQL::class,
            Redis::class,

            RabbitMQ::class,
            Docker::class,
            Git::class            
        ];
    }

    public function getLearningStack(): array
    {
        return [
            PostgreSQL::class,
            MongoDB::class,
            Jenkins::class,
            Nginx::class,
            Linux::class
        ];
    }

    public function getFunFact(): array
    {
        return [
            'There are two ways to write error-free programs; only the third one works!'
        ];
    }
}
```
