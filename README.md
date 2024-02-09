## Development

1. Clone the repository:

```bash
git clone https://github.com/arvindpndit/stack-doubts.git
```

2. Enter the project directory:

```bash
cd stack-doubts
```

3. Install the dependencies:

```bash
npm i
```

4. Configure the env vars as described below -

   1. Create a new file named `.env.local` in your project's root directory
   2. Open the `.env.local` file in a text editor.
   3. Set the values of the environment variables with the appropriate values

```dotenv
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_TINY_URL_API_KEY=your_tinyurl_api_key
MONGODB_URL=your_mongodb_connection_url
WEBHOOK_SECRET=your_webhook_secret
```

5. Start the development server with:

```bash
npm run dev
```
