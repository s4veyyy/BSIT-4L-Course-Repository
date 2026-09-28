# Cloud Storage Types Research

## Comparison Table

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in blocks that can be attached to a server and used like a traditional hard drive. | Best used for operating systems, databases, and applications that need fast and direct storage access. | AWS EBS |
| File Storage | Stores data as files in folders and directories that can be accessed by multiple users or systems. | Best used for shared files, documents, and applications that need a common file system. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier. | Best used for large amounts of unstructured data such as images, videos, backups, and other media files. | AWS S3 |

## Recommendation for the Client

I would recommend Object Storage for the photo-sharing application because it is designed to store large amounts of unstructured data such as user-uploaded images. It can also provide scalable and accessible storage for the application's growing collection of photos.
