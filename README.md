## Getting Started

1. First, install node modules:

```bash
npm install
or
yarn
```

2. Second, create .env file

```bash
## Environment ##
NODE_ENV=development

## Server ##
PORT=3001
HOST=localhost
DATABASE_URL=mongodb://localhost:27017
ACCESS_TOKEN_KEY=ACCESS_TOKEN
REFRESH_TOKEN_KEY=REFRESH_TOKEN
ACCESS_TOKEN_LIFE=10m
REFRESH_TOKEN_LIFE=10m
HASH_CODE=8
```

3. After, run the development server:

```bash
npm run dev
or
yarn dev
```

Open http://localhost:3001 with your browser to see the result.
