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
                    'company' => 'HiTrav',
                    'position' => 'Back-End Developer',         
                ],
            ],
        ];
    }

    public function getKnowledgeStack(): array
    {
        return [
            PHP::class,
            Laravel::class,
            Symfony::class,
            Docker::class,
            MySQL::class,
            Redis::class,
            Git::class
        ];
    }

    public function getLearningStack(): array
    {
        return [
            GoLang::class,
            PostgreSQL::class,
            RabbitMQ::class,
            GraphQL::class,
            MongoDB::class,
            Jenkins::class,
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
