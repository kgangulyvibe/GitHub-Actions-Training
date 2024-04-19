# GitHub-Actions-Training

This repository is used for training purposes for GitHub Actions.

Table of Contents:
- [GitHub Actions](#github-actions)
- [Workflows](#workflows)
- [Events](#events)
- [Jobs](#jobs)
- [Steps](#steps)
- [Actions](#actions)
- [Runners](#runners)

# Introduction

## GitHub Actions

GitHub Actions is a feature that allows you to automate tasks in your repository. You can create custom workflows to build, test, package, release, and deploy any code project on GitHub.

## Workflows

A workflow is a configurable automated process made up of one or more jobs. You must create a YAML file to define your workflow configuration.

## Events

Events are specific activity triggers that start a workflow. You can configure a workflow to run when specific activity on GitHub happens.

## Jobs

Jobs are a collection of steps that execute on the same runner. By default, jobs run in parallel.

## Steps

Steps are a set of tasks that execute commands. A step can be a shell command or an action.

## Actions

Actions are standalone commands that are combined into steps to create a job. You can create your own actions or use actions created by the GitHub community.

## Runners

Runners are servers that run your jobs in a workflow. GitHub provides hosted runners for Linux, Windows, and macOS. You can also host your own runner.

# Training material

This workflow demonstrates how to create a reusable workflow in GitHub Actions. It defines a single job that greets a person whose name is passed as an input parameter. Additionally, it outputs the current time after greeting.
