
## Getting Started

This project demonstrates a simple Flutter app using Supabase authentication with Google and Facebook. Follow the steps below to set up and run the project locally.

## Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) installed
- A [Supabase](https://supabase.com/) account

## Project Setup

####	Clone the Repository git
- `git clone https://github.com/jecode93/user_authentication.git`
- `cd user_authentication`

#### Install Dependencies
- Run the following command to install the necessary packages:
`flutter pub get`

#### Create a Supabase Project
- Go to [Supabase](https://supabase.com/) and create a new project.
- From the Supabase dashboard, go to Connecting to your new project section > Project API to get your API URL and Anon Key.

#### Configure OAuth Providers in Supabase
- In the Supabase dashboard, go to Authentication > Providers.
- Enable Google and Facebook providers and configure them with the required credentials.


#### Create a .env File

In the root directory of the project, create a file named `.env` with the following content, replacing `your-supabase-url` and `your-anon-key` with your Supabase details:

- `SUPABASE_URL=https://your-supabase-url.supabase.co`
- `SUPABASE_ANON_KEY=your-anon-key`

#### Running the App
Run the following command to start the application:

- `flutter run`
