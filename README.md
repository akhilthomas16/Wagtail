# Wagtail Project

This is a content management system built with Wagtail, a Django-based CMS framework.

## Setup

1. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run migrations:
```bash
python manage.py migrate
```

4. Create superuser:
```bash
python manage.py createsuperuser
```

5. Start development server:
```bash
python manage.py runserver
```

## Features

- Django-based CMS
- Customizable admin interface
- Built-in SEO tools
- Image manipulation
- Content versioning

## Contributing

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

#### - Generate Secret Key ( ! Important for deployment ! )
```
python manage.py shell
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
exit()
```
## License

This project is licensed under the MIT License.