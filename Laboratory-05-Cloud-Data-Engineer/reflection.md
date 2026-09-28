# Mission Reflection

Working with object storage in this laboratory activity gave me a much clearer picture of how cloud storage really works. Object storage is better suited for storing millions of photos compared to a traditional block storage hard drive because it is built to scale — instead of managing data as fixed blocks on a single disk, object storage stores each file as an independent object with its own metadata, which makes it easier to retrieve, organize, and scale across many servers as the number of files grows into the millions.

Using Docker made deploying MinIO surprisingly fast. Instead of manually installing and configuring an object storage server, one command pulled the image and had the server running within minutes. This also made it easy to redeploy — when my KillerCoda session expired partway through the activity and the container disappeared, I was able to bring MinIO back up again with the same command instead of starting the whole setup from scratch.

A "bucket" in cloud storage is essentially a container for organizing objects, similar to a top-level folder, but with its own access permissions and settings. In this activity, the client-photos bucket acted as the dedicated storage space for the client's uploaded images.

Large enterprise companies typically protect against data loss by replicating data across multiple servers, drives, and even physically separate data centers. If one server fails, copies of the data still exist elsewhere, so the system keeps running without losing information.

Doing this activity also made me more comfortable with the Linux command line. I ran into a real problem when I accidentally deleted my running container using docker rm right after deploying it, which taught me to be more careful about which commands to run and when. Troubleshooting that on my own, and verifying the fix using docker ps, made me more confident that I can recover from mistakes instead of getting stuck.

---

*AI Disclosure: I used Claude AI to help troubleshoot Docker/MinIO deployment issues during this activity and to help draft and organize this reflection. I reviewed and edited the content to reflect my own experience and understanding.*
