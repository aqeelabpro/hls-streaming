# CORS Config

```
[
  {
    "AllowedHeaders": [
      "*"
    ],
    "AllowedMethods": [
      "GET",
      "POST",
      "DELETE",
      "PUT"
    ],
    "AllowedOrigins": [
      "*"
    ],
    "ExposedHeaders": []
  }
]

```


# Bucket Permissions
```
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "Statement1",
      "Effect": "Allow",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:.hls-test.piyushgarg.dev/*"
    }
  ]
}
```
