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


### describe target groups by target group arns

```bash
aws elbv2 describe-target-groups --target-group-arns arn:aws:elasticloadbalancing:ap-northeast-2:915486611144:targetgroup/tg-event-api-dev/27f2811d25fcbf78
```
