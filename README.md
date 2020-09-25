# Tools for AWS lambda deployment and logging

`poetry add aws-sam-cli`

sam init

`sam init --runtime python3.7 --dependency-manager pip --name lambda-logging`

cd in to new directory

`sam build`

`sam deploy --guided --profile it-dev-poweruser`

Delete lambda function 
`aws cloudformation delete-stack --stack-name samFunStackName --region us-west-2 --profile it-dev-poweruser`

# My workflow
`sam init --runtime python3.7 --dependency-manager pip --name lambda-logging`

Move over template.yml to use your own

