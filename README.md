# hello-world-docker-action

This actions prints "Hello World" or "Hello" + tthe me of a person to greet to the log.

## Inputs

## `who to greet`

**Required** The name of the person to greet. Default `"World"`

## Outputs

## `Time`

The time we greeted you.

## Example Usage

```{yaml}

uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the octocat'

```

