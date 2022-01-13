
### Oi, eu sou o Mateus e bem-vindo ao meu GitHub.

<a href="https://costamateus.com.br/">
  <img align="left" alt="MLC" width="22px" src="https://www.costamateus.com.br/favicon.ico" />
</a>
<a href="https://www.linkedin.com/in/costamateus6/">
  <img align="left" alt="LinkedIn Mateus" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
<a href="https://www.instagram.com/mateuslc6/">
  <img align="left" alt="Instagram Mateus" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a href="https://www.facebook.com/costamateus6/">
  <img align="left" alt="Facebook Mateus" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.13.0/icons/facebook.svg" />
</a>

![](https://visitor-badge.glitch.me/badge?page_id=costamateus.costamateus)

<br />

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
            NodeJs::class,
            Sql::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
