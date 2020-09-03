# aws lambda

> CLI for AWS Lambda
> More information: <https://aws.amazon.com/cli>.

- List lambda functions:

`aws lambda list-functions`

- Invoke a function synchronously (default: RequestResponse):

`aws lambda invoke --function-name {{function-name}} --payload {{payload}} {{out}}`

- Invoke a function asynchronously (default: RequestResponse):

`aws lambda invoke --function-name {{function-name}} --invocation-type Event --payload {{payload}} {{out}}`
