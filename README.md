# Ubuntu Pkg Cleanup
This action removes large Ubuntu packages that you might not need

## Usage

### Example Workflow
```yaml
name: Clear large Ubuntu packages  

jobs:
  my-job:
    name: Delete all caches
    runs-on: ubuntu-20.04

    steps:
      - name: Clear caches
        uses: edoapra/ubuntu-pkg-cleanup@main
```
