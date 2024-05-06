A Bun-based HTTP server responding with system info
# How to build:
To install bun:
`curl -fsSL https://bun.sh/install | bash -s "bun-v1.0.0`
Add Bun to your path
`BUNPATH = $HOME/.bin/bin`
Install dependencies:
`bun install`
Lint:
`bunx eslint .`
Test:
`bun test`
Build Docker image:
`docker build . -t buninfo:<build_tag>`



