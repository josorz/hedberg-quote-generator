# Mitch Hedberg Jokes API

REST API for random Mitch Hedberg quotes

## Usage

### `GET` /

```json
{
  "quote": "I used to do drugs. I still do, but I used to, too."
}
```

### `GET` /text

```text
I order the club sandwich all the time. And I’m not even a member, man. I don’t know how I get away with it.
```

### `GET` /quotes

> [!WARNING]  
> This response format may change.

```ts
[
    ...,
    "I'm sick of following my dreams. I'm just gonna ask where they're going and hook up with them later.",
    "I met the girl who works at the DoubleTree front desk. She gave me her phone number, it's zero.",
    ...,
]
```

## Development

```shell
pnpm dev
```

## License

MIT
