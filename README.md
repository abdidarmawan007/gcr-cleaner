# gcr cleaner
automated gcr images cleaner with bash script

```
gcrgc.sh cleans up tagged or untagged images pushed before specified date
for a given repository (an image name without a tag/digest).
USAGE:
  gcrgc.sh REPOSITORY DATE
EXAMPLE
  gcrgc.sh asia.gcr.io/zeus-cloud/develop-golang 2019-04-01
  would clean up everything under the asia.gcr.io/zeus-cloud/develop-golang repository
  pushed before 2019-04-01.
```
  
  ### example
  bash gcrgc.sh asia.gcr.io/zeus-cloud/develop-golang 2019-04-01
