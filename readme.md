```yaml
name: Generate Documentation

on:
  push:
    branches: ["master"]
  workflow_dispatch:
  
jobs:
  main:
    uses: CesarBerriot/generate-writerside-docs/.github/workflows/action.yml@v1.0.0
    with:
      instance: 'Writerside/in'
```