## Run it local without Docker

### Prerequisite

- Install `npm`

#### Start Server/backend:

```
cd mern/server
npm install
npm start
```

#### Start Client/frontend (on port 5173):

```
cd mern/client
npm install
npm run dev
```

<img width="1790" alt="Screenshot 2024-08-31 at 11 07 58 PM" src="https://github.com/user-attachments/assets/f414230b-8bd6-4393-b8de-6a10444a8dfd">

## Using Docker Compose

`docker compose up -d`


## Used Distroless images in multi-staging Dockerfile to reduse the size of final image (from 1.79 GB to 213 MB)  and Reduced Attack Surface
![image](https://github.com/user-attachments/assets/35bb2d03-4f78-4228-ac25-2db5600f6e75) 

