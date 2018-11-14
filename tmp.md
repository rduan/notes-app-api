npx aws-api-gateway-cli-test \
--username='admin@e.com' \
--password='Passw0rd!' \
--user-pool-id='ap-southeast-1_SCLaM3fGQ' \
--app-client-id='6hu418k8iui5vk02v547aqed0b' \
--cognito-region='ap-southeast-1' \
--identity-pool-id='ap-southeast-1:3d3a1a75-ad0b-4fb5-abad-6a1cfc6ecb55' \
--invoke-url='https://zrqzrhzgkk.execute-api.ap-southeast-1.amazonaws.com/dev' \
--api-gateway-region='ap-southeast-1' \
--path-template='/notes' \
--method='POST' \
--body='{"content":"hello wwwd", "attachment":"hello.jpg"}'

npx aws-api-gateway-cli-test \
--username='admin@e.com' \
--password='Passw0rd!' \
--user-pool-id='ap-southeast-1_SCLaM3fGQ' \
--app-client-id='6hu418k8iui5vk02v547aqed0b' \
--cognito-region='ap-southeast-1' \
--identity-pool-id='ap-southeast-1:3d3a1a75-ad0b-4fb5-abad-6a1cfc6ecb55' \
--invoke-url='https://zrqzrhzgkk.execute-api.ap-southeast-1.amazonaws.com/dev' \
--api-gateway-region='ap-southeast-1' \
--path-template='/notes' \
--method='POST' \
--body='{"content":"hello wwwd", "attachment":"hello.jpg"}'



apig-test \
--username='admin@e.com' \
--password='Passw0rd!' \
--user-pool-id='ap-southeast-1_SCLaM3fGQ' \
--app-client-id='6hu418k8iui5vk02v547aqed0b' \
--cognito-region='ap-southeast-1' \
--identity-pool-id='ap-southeast-1:3d3a1a75-ad0b-4fb5-abad-6a1cfc6ecb55' \
--invoke-url='https://zrqzrhzgkk.execute-api.ap-southeast-1.amazonaws.com/dev' \
--api-gateway-region='ap-southeast-1' \
--path-template='/notes' \
--method='POST' \
--body='{"content":"hello wwwd","attachment":"hello.jpg"}'

apig-test \
--username='admin@e.com' \
--password='Passw0rd!' \
--user-pool-id='ap-southeast-1_SCLaM3fGQ' \
--app-client-id='6hu418k8iui5vk02v547aqed0b' \
--cognito-region='ap-southeast-1' \
--identity-pool-id='ap-southeast-1:3d3a1a75-ad0b-4fb5-abad-6a1cfc6ecb55' \
--invoke-url='https://zrqzrhzgkk.execute-api.ap-southeast-1.amazonaws.com/dev' \
--api-gateway-region='ap-southeast-1' \
--path-template='/notes' \
--method='GET' \
--body='{}'