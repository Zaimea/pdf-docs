---
title: How to install package
description: How to install package
github: https://github.com/zaimea/pdf-docs/edit/main/
sections: 
    installation : 'Install'
    publish : 'Publish'
---

# Metrics

[[TOC]]

## Instalation

```json
"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/zaimealabs/pdf"
        }
    ]
```

```bash
composer require zaimealabs/pdf
```

## Publish

```bash
    php artisan vendor:publish --tag=pdf
```