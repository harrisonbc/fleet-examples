  

  We need to create an image pull secret to pull from application-collection


Additional Components
In addition to the SUSE Registry secret a number of components must be available:
Kubernetes Secrets
sprcert - contains the TLS Certificate for the SUSE Private Registry Endpoint.
s3-ca - contains the CA certificate used to sign the S3 endpoint certificate.


Storage Classes to create PVCs for image data
   px-postgress
   px-jobservice
   px-redis
   px-trivy


S3 Bucket for image data
spr

