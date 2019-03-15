## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_shawnsService
package-version: 2010-02-03
azure-arm: true
```

### Tag: package-2010-02-03 and ruby

These settings apply only when `--tag=package-2010-02-03 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2010-02-03' && $(ruby)
namespace: Microsoft.Employee
output-folder: $(ruby-sdks-folder)/shawnsService
```
