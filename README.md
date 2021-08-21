```php
<?php

namespace GitHub\SMhdHsn;

/**
 * @email m2hdtl@gmail.com
 * @location Tehran, Iran
 * @birth 1998-08-23
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
            PHP::class,
            Laravel::class,
            Symfony::class,
            MySQL::class,
            Redis::class,
            Git::class
        ];
    }
    
    public function getKnowledgeToGain(): array
    {
        return [
            GoLang::class,
            PostgreSQL::class,
            RabbitMQ::class,
            GraphQL::class,
            MongoDB::class,
            Jenkins::class,
            Docker::class,
            Linux::class
        ];
    }
    
    public function getFunFact(): string
    {
        return 'I like my coffee black, just like my Metal.';
    }
}
```
