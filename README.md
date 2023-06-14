# Test Resources
The next repository contains public util resources to allow us test spinnaker features.
We can retrieve resources directly using github api:
```
https://api.github.com/repos/armory-io/test-resources/contents
```
For example to retrieve helm chart inside directory test-resources/helm_chart, you can call:
```
https://api.github.com/repos/armory-io/test-resources/contents/helm_chart/foo-0.1.0.tgz?ref=master
```
