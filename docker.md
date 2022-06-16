yawsso -e -p dev.AWSAdministratorAccess

docker build -t latest .
docker tag x x
aws ecr get-login-password --profile x | docker login --username AWS --password-stdin 236788474445.dkr.ecr.us-east-1.amazonaws.com
docker push x]
