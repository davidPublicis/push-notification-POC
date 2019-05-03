yarn install and cd client yarn install

Get VAPID: ./node_modules/.bin/web-push generate-vapid-keys


// Create .env file, add following lines and fill in with the VAPID IDs created.
file location: ./.env

UBLIC_VAPID_KEY=
PRIVATE_VAPID_KEY=
WEB_PUSH_CONTACT="mailto: test@test.com"



// Create .env file in client folder, add following lines and fill in with the VAPID IDs created.
file location: ./client/.env

REACT_APP_API_URL=http://localhost:9000
REACT_APP_PUBLIC_VAPID_KEY=
