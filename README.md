# flutter_db_supabase

flutter pub add supabase_flutter

flutter pub add flutter_dotenv

Make sure you have this in pubspec.yaml:

flutter:

  assets:

    - assets/.env

Make assets/ folder in the project and create an .env file with:

SUPABASE_ENV=

SUPABASE_ANONKEY=

Create a project and new table called 'notes' in Supabase, add a new column (field) named 'content', the type is 'text'.

