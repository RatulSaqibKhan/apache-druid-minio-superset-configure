# Installation MinIo

## To Do
  1. Open terminal in `minio` directory
  2. run `cp .env.example .env` to create a copy of `.env.example` in `.env`
  3. Setup the environment variables in `.env`
      ```
        IMG_TAG=RELEASE.2022-11-26T22-43-32Z
        EXPOSE_PORT=4094
        MINIO_ROOT_USER=ROOTUSER
        MINIO_ROOT_PASSWORD=PASSWORD
      ```
  4. run `docker compose up -d`
  5. MinIO server will be running in `http://localhost:4094/`
  6. Login with the username and password defined in `.env`

## MinIO GUI Screenshot
![MinIO GUI](../images/minio.png)