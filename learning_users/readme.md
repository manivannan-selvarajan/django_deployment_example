# issues in auth user file to do the following commands
$python manage.py migrate admin zero
$python manage.py migrate auth zero
$python manage.py migrate contenttypes zero
$python manage.py migrate sessions zero

$python manage.py makemigrations basic_app

$python manage.py migrate

