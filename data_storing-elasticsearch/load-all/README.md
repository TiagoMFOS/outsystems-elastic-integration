# Load all Elasticsearch configurations

## How to implement all configurations at once

Using Kibana's `Dev Tools`, simply copy the contents of all-configs.json into your Kibana console and execute all commands.

This will, in turn, perform the following operations:
1. Load the ILM Policy
2. Load the Index Template
3. Load the Transform for request breakdown data, and bootstrap the new index
4. Initiate the Transform automatically
