<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-octicons-context-processor.svg?maxAge=3600)](https://pypi.org/project/django-octicons-context-processor/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-octicons-context-processor.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-octicons-context-processor.py/actions)

### Installation
```bash
$ [sudo] pip install django-octicons-context-processor
```

##### `settings.py`
```python
TEMPLATES = [
    {
        # …
        'OPTIONS': {
            'context_processors': [
                'django_octicons_context_processor.context_processors.octicons',
            ],
        },
    },
]
```

##### Templates
```html
{{ octions.package_16px }}
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
