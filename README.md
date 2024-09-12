# hello-aws-cli
hello aws cli

## aws caller identity

```bash
aws sts get-caller-identity
```

## aws elbv2


### load balancers list

```bash
aws elbv2 describe-load-balancers
```

### load balancer listeners

```
aws elbv2 describe-listeners --load-balancer-arn {load balancer arn}
```
