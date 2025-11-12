# mapstep.io back-end application

Tech stack:
- **Python** - back-end programming language
- **Django** – Python-based web Django REST framework
- **GeoDjango** - geospatial extension of Django's ORM
- **PostgreSQL + PostGIS** - primary database service with native support for geometric and geographic data
- **PyProj** - geospatial library for coordinate system conversion
- **Google Maps Geocoding API** - latitude/longitude calculations API
- **djangorestframework-simplejwt** - cookie-based JWT authentication
- **django-storages + boto3** - integration with AWS S3 for media and file uploads

Back-end deployment:
- **Railway** - back-end hosting with web and postGIS services
- **AWS S3** – cloud-based file storage
- **Gunicorn + Whitenoise** - production web server and static file management

Prototyping & Architecture:
- **Figma** - Django back-end architecture, entity relationship diagrams (ERDs)

External data source:
- [Los Angeles County Assessor's portal](https://portal.assessor.lacounty.gov/)