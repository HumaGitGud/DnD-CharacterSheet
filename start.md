# To start application:

## Local:

1. cd into express-be and run: `<npm i>` then create .env with vm mysql user credentials
2. cd into react-fe   and run: `<npm i>` then create .env with VITE_API_BASE_URL=VM URL IP and VITE_API_PORT=port at which vm serves
3. open react-fe and run `<npm run dev>`

## Inside VM:

1. cd into express-be and run: `<npm i>` then create .env with vm mysql user credentials
2. `<npm run dev>`
3. open local react-fe and run `<npm run dev>`

> **Note:** this version of app doesnt serve front-end in the VM, work that's left here is:
> 1. Host/serve front-end in vm using pm2 and ecosystem configuration file
> 2. Create a cli script for new vm machines to avoid running million commands for setup (all setup commands in 'vm command history')
> 3. Further polish the app (user accounts/auth, styles, etc.)