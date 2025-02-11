# Ubuntu Pkg Cleanup
This action removes large Ubuntu packages that you might not need

## Usage

### Example Workflow
```yaml
name: Clear large Ubuntu packages  

jobs:
  my-job:
    name: test
    runs-on: ubuntu-20.04

    steps:
      - name: Remove Ubuntu packages
        uses: edoapra/ubuntu-pkg-cleanup@main
```
