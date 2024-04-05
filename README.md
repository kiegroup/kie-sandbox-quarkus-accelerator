# KIE Sandbox Quarkus Accelerator

This git repository contains all the files necessary to run a Quarkus application with .DMN and .BPMN files.

On KIE Sandbox it's used as an Accelerator, to be applied to a set of Decision and Workflow files, making it fully buildable and deployable.

## Branches
- `main`: Should not be used.
- `0.0.0`: The latest version of this Accelerator. Pull requests should point to this branch and new tags are generated from it on each release.
- `template`: Legacy branch with a Quarkus template, created before the concept of Accelerators was implemented in KIE Sandbox.

## Tags
Tags are generated alongside [kie-tools](https://github.com/apache/incubator-kie-tools/) releases and match the latest version released (i.e. `0.27.0`).

## Using this Accelerator on KIE Sandbox
  - Go to [KIE Sandbox](https://sandbox.kie.org);
  - Create your Decision and/or Workflow files;
  - Click on `Add Accelerator` and select `Quarkus...`;
  - Click `Apply`;
  - When the Accelerator is successfully applied to your set of files, create a git repository from it (if not created already);
  - Clone it to your local environment;
  - Run with `mvn quarkus:dev`.
