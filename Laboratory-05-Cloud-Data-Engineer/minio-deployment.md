# MinIO Deployment Documentation

## Docker Command Used

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
elestio/minio server /data --console-address ":9001"
```

## Web Console Access

- **Port used:** 9001
- Accessed via the KillerCoda "Traffic / Ports" custom port feature, which forwarded port 9001 to a public URL for the MinIO web console.

## Bucket Created

- **Bucket name:** `client-photos`

## Environment Variables Explained

- `-e "MINIO_ROOT_USER=cloudadmin"` — Sets the admin username used to log in to the MinIO console. This acts as the root/superuser account for the storage server.
- `-e "MINIO_ROOT_PASSWORD=CloudNova2026!"` — Sets the admin password paired with the root user above. Together, these two variables define the login credentials for administering the MinIO server.
