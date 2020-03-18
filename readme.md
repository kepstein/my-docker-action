# Hello world docker action

Following along with the [GitHub tutorial for Docker based GitHub Action](https://help.github.com/en/actions/building-actions/creating-a-docker-container-action). This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: kepstein/my-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
