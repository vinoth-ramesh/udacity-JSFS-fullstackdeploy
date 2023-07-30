# Hosting a Full-Stack Application


### Infrastrucure Requirements

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. `https://learn.udacity.com/nanodegrees/nd0067/parts/cd0295/lessons/fb92ce6e-7365-482f-a713-d98b9d70e1ca/concepts/2102d496-be9a-4183-8d15-0d70f71dd7fe`

2. In AWS, provision a s3 bucket for hosting the uploaded files. `https://learn.udacity.com/nanodegrees/nd0067/parts/cd0295/lessons/fb92ce6e-7365-482f-a713-d98b9d70e1ca/concepts/2102d496-be9a-4183-8d15-0d70f71dd7fe`

3. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.

4. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.

5. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

