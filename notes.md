
sls invoke local --function create --path mocks/create-event.json

sls invoke local --function get --path mocks/get-event.json

aws cognito-idp sign-up \
  --region ap-southeast-1 \
  --client-id 6hu418k8iui5vk02v547aqed0b \
  --username admin@example.com \
  --password Passw0rd!

  aws cognito-idp admin-confirm-sign-up \
  --region ap-southeast-1 \
  --user-pool-id ap-southeast-1_SCLaM3fGQ \
  --username admin@example.com

  npx aws-api-gateway-cli-test \
  --username='admin@example.com' \
  --password='Passw0rd!' \
  --user-pool-id='ap-southeast-1_SCLaM3fGQ' \
  --app-client-id='6hu418k8iui5vk02v547aqed0b' \
  --cognito-region='ap-southeast-1' \
  --identity-pool-id='ap-southeast-1:ca49c4f6-5a63-4511-a1b6-c85f2a83e2c0' \
  --invoke-url='https://zzmtnlmwjk.execute-api.ap-southeast-1.amazonaws.com/dev' \
  --api-gateway-region='ap-southeast-1' \
  --path-template='/notes' \
  --method='POST' \
  --body='{"content":"hello world","attachment":"hello.jpg"}'

  serverless deploy function -f create

  