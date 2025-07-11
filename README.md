# Buildkite Starter Pipeline Example

[![Build status](https://badge.buildkite.com/f9b46d96710d254e34229ba68bb8797d0b8f1e64ac5abfecb9.svg?branch=main)](https://buildkite.com/buildkite/starter-pipeline-example/builds/latest?branch=main)
[![Add to Buildkite](https://img.shields.io/badge/Add%20to%20Buildkite-14CC80)](https://buildkite.com/new)

This repository is a friendly starting point for learning how [Buildkite](https://buildkite.com/) pipelines work.

👉 **See this example in action:** [buildkite/starter-pipeline-example](https://buildkite.com/buildkite/starter-pipeline-example/builds/latest?branch=main)

See the full [Getting Started Guide](https://buildkite.com/docs/guides/getting-started) for step-by-step instructions on how to get this running, or try it yourself:

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)



The pipeline is platform agnostic, which means it can run on any infrastructure. Its behavior is defined in [.buildkite/pipeline.yml](.buildkite/pipeline.yml), including steps to build, test, and deploy. These steps describe launching a shiny new rocket to the moon. 🚀🌕

## Create a pipeline

You'll need a Buildkite account and a running agent to use the pipeline. If you need help setting up Buildkite, see [Getting started](https://buildkite.com/docs/tutorials/getting-started).

With Buildkite setup, you can quickly create a new pipeline by selecting **Add to Buildkite**. This prefills the pipeline details using [template.yml](.buildkite/template.yml) and includes a command to upload the pipeline definition in [pipeline.yml](.buildkite/pipeline.yml).

## License

See [LICENSE](LICENSE) (MIT)
