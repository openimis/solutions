# solutions
repository that will host the configuration files for different flavor of openIMIS


# each folder match a solution:
- coreMIS


# TODO

- update the dist_dkr to mount the fixtures files
- change the entrypoint.sh to load the fixture if new setupt (we can say that it is a new setup if there no core configuration, because solution builder will always have a core config for the menu at least)

# how populate

0. start from empty
1. copy the dist_dkr without the compose.yml
2. run solution builder
3. past the outputs in the repo

