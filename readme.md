<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'Studying in' => 'VIT Bhopal',
                'position' => 'Student'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            React::class,
            Javascript::class,
            Python::class,
            C++::class,
            HTML::class,
            CSS::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
