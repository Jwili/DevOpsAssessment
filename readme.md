# Kaleidocode DevOps Assessment

## Overview

This assessment intention is to:
   * Understand knowledge and potential for knowledge of a candidate
   * Create talking points with a candidate about DevOps techniques and tools

Knowledge of how this code works is __not__ required


## Goal
    
   * The Candidate will attempt to set up a **build and test** cycle for a [Continuous Integration pipeline](https://dzone.com/articles/learn-how-to-setup-a-cicd-pipeline-from-scratch) for DevOpsAssessment.sln in the DevOpsAssessment folder


### Tools

   * CI Engine
     * Gitlab CI is the recommended 
       * ```Note: As long as assessors are able to view the pipeline in action, any CI engine can be used.```
   * Code tooling
     * [dotnet cli](https://docs.microsoft.com/en-us/dotnet/core/tools/) should be used for commands for Building and testing of the components


### Extra but not required

   * Docker image to be pushed on successful build
   * Status Badges to be displayed on the readme.md or repository header
   * Different pipeline steps for builds inteded for develop and production respecitvely
   * Create a branch using the patch for `BrokenBuild` to show the build stage does fail
   * Create a branch using the patch for `BrokenTest` to show the test stage does fail
