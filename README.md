# Projeto ReactJS | Hiring Coders
## AWS <> DevOps

### Politicas de bucket:
`{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "AllowPublicReadAccess",
      "Effect": "Allow",
      "Principal": "*",
       "Action": [ "s3:GetObject" ],
       "Resource": [ "arn:aws:s3:::example-bucket/*" ]
     }
  ]
}`

### Template de pipeline
[clique aqui](template.yml)

### Link público para o Bucket:
[clique aqui](http://hcreacts3.s3-website-us-east-1.amazonaws.com/)


### GitHub Actions


### Professor Douglas Morais