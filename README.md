# rust-image :confetti:

A rust development environment with fish, vim, and exa (as a "replacement" for ls).

# A sample run command, mounting local code dir as the working dir of the container:

```
docker run -it -d \
--hostname="rust" \
--name="rust" \
-v ~/code/rust:/code \
-w /code \
doqr/rust:latest
```

# Enter the container:
```
docker exec -it rustainer /usr/bin/fish
```
