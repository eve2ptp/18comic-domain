**clash custom rules**

```yaml
rule-providers:
  18comic:
    type: http
    behavior: domain
    url: "https://raw.githubusercontent.com/eve2ptp/18comic-domain/main/domain.txt"
    path: ./ruleset/18comic.yaml
    interval: 86400

rules:
  - RULE-SET,18comic,vless-warp
```
