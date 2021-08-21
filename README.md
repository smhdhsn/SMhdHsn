```php
<?php

namespace GitHub\SMhdHsn;

/**
 * @birth 1998-08-23
 * @location Tehran, Iran
 * @email m2hdtl@gmail.com
 */
class About extends Me
{
    public function __construct()
    {
        echo 'Hi There !';
    }
    
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'HiTrav',
                'position' => 'Back-End Developer'         
            ]
        ];
    }

    public function getCurrentKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Symfony::class,
            MySQL::class,
            Redis::class,
            Git::class
        ];
    }
    
    public function setToolsToLearn(): array
    {
        return [
            PostgreSQL::class,
            RabbitMQ::class,
            GraphQL::class,
            MongoDB::class,
            Jenkins::class,
            Docker::class,
            Linux::class,
            Go::class
        ];
    }
    
    public function getFunFact(): string
    {
        return 'I like my coffee black, just like my Metal.';
    }
}
```
