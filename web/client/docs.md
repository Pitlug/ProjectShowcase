# NPM Setup

## Pull the Node.js Docker image:
docker pull node:25-alpine

## Create a Node.js container and start a Shell session:
docker run -it --rm --entrypoint sh node:25-alpine

## Verify the Node.js version:
node -v # Should print "v25.7.0".

## Verify npm version:
npm -v # Should print "11.10.1".

