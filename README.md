# clocksimulator

A clean, fullscreen analog clock simulator built with plain HTML, CSS, and JavaScript.

## Timezone support

By default the clock shows your local time. To display a different timezone, add the `tz` query parameter with any valid [IANA timezone identifier](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones):

```
https://clocksimulator.com/?tz=America/New_York
https://clocksimulator.com/?tz=Asia/Tokyo
https://clocksimulator.com/?tz=Europe/Helsinki
https://clocksimulator.com/?tz=UTC
```

If the value is invalid or omitted, the clock falls back to your local timezone.

## License

MIT. See `LICENSE`.
