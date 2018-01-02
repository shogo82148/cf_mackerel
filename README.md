# cf_mackerel
An AWS CloudFormation Template for [Mackerel AWS Integration](https://mackerel.io/docs/entry/integrations/aws).

## Usage

```
aws cloudformation create-stack --stack-name "MackerelIntegrationIamUser" \
    --template-body https://shogo82148.github.io/cf_mackerel/mackerel.yaml \
    --capabilities CAPABILITY_NAMED_IAM
```

## Related Projects

- [Tomohiro/tf_mackerel](https://github.com/Tomohiro/tf_mackerel): A Terraform module for Mackerel AWS Integration.

## License

This is licensed under the The Unlicense. See LICENSE.
