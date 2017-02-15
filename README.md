# Realm Object Server container image

## Usage

### Test

```
docker run --rm -p 9080:9080 wearemakery/realm-object-server:1.0.3-231
```

### Exposed ports

- `9080`: http, ws
- `9443`: https, wss

### Volume

- `/var/lib/realm/object-server`