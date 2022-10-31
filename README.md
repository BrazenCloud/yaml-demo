# BrazenCloud YAML demo

This repository serves as an example of how the [BrazenCloud.YAML](https://github.com/brazencloud/yaml) module can be used to express BrazenCloud Jobs and Connectors in YAML and sync them to BrazenCloud.

## Explanation

This repository is designed to take any `.yaml` files in the `yamls` directory and sync them to BrazenCloud.

In the workflow, under the `syncJobs` job and the `Sync Jobs` task, the script is pointed at the `yamls` folder. this could easily be changed or could be adjusted to recursively search the directory.

## Usage

If you would like to express your BrazenCloud resources in YAML, you can fork this repository or simply create your own by copying this one. By default the workflow is set to run on pushes to the `main` branch.

In the future, we will add a feature to implement a PR function to output what would change rather than making any changes.