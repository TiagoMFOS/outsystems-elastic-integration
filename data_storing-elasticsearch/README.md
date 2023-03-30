# How to use the Elasticsearch accelerators

## About

These Elasticsearch accelerators are in fact configurations for the indices that will hold the monitoring data extracted from the OutSystems platform.

## Run configurations

You have two choices to load these configurations onto Elasticsearch. The first one is aimed at experienced users that just want a condensed, no-fuss approach at loading what is needed:

1. [Load all necessary configurations](load-all/README.md)

The second approach is to perform the load step-by-step. It is recommended for first-time users, or people who simply want to better understand what configurations are involved:

1. [Apply the Index Lifecycle Management (ILM) Policies](ilm-policies/README.md).
2. [Apply the Index Templates](index-templates/README.md)
3. [Set up the Transforms](transforms/README.md).
