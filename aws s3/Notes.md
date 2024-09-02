
# what is object storage (Object-Based Storage)?
 Object storage is a datastorage architecture that manages data as objects, as opposed to other storage architectures

 - S3 provides you with *unlimited storage(Some restrictions at someplace)
 - You don't need to think about its underlying infrastructure
 - The S3 Console provides an interface for you to upload and access your data

 **s3 object**
Objects contain your data. They are like files.  
objects may consists of :
- **key** this is the name of the object
- **value** the data itself made up of sequence of bytes
- **version id** when versioning enabled, the version of object
- **Metadata** additional information attached to the object

**S3 Bucket**  
Buckets hold objects. Buckets can also have folders which in turn hold objects

- S3 is a universal namespace. So bucket names must be unique (Like domain names)

- You can store individual object from 0 bytes to 5 Terrabytes in size

## AWS S3 command line operations


Keypoints To Consider :

> Storage class is at object level 
> ![alt text](aws s3/Storageclasses-fee-structure.png)
![alt text](aws s3/Storageclass-oneshot.png)