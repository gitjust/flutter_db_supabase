# flutter_db_supabase

flutter pub add supabase_flutter

flutter pub add flutter_dotenv

Make sure you have this in pubspec.yaml:

flutter:

  assets:

    - assets/.env

Make assets/ folder in the project and create an .env file with:

SUPABASE_URL=

SUPABASE_ANONKEY=

Create a project and new table called 'notes' in Supabase, uncomment Enable Row Level Security, check Enable Realtime, then add a new column (field) named 'content', the type is 'text'.

Go to project overview in Supabase to find your Supabase URL and Anon Key, or click Connect then open tab App Frameworks to see your keys.

