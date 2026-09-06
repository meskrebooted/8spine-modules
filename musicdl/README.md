# 8SPINE MusicDL Module - spotiflac bridge

Modulo STREAM per 8SPINE che usa MusicDL direttamente per ottenere stream lossless FLAC senza passare per SpotiFLAC Mobile.

## Installazione in 8SPINE

### Via Source URL
1. Apri 8SPINE → Settings → Sources
2. Aggiungi URL: `https://raw.githubusercontent.com/meskrebooted/8spine-modules/main/index.json`
3. Il modulo apparirà in elenco

### Via Deep Link
```
eightspine://install?url=https://raw.githubusercontent.com/meskrebooted/8spine-modules/main/index.json
```

## File
- `musicdl_stream.8spine` - Modulo STREAM
- `manifest.json` - Metadati modulo
- `index.json` - Index per 8SPINE

## API usata
- `https://www.musicdl.me` - Download lossless

## Note
Non usa SpotiFLAC Mobile per evitare Cloudflare challenge. Le richieste fetch dal modulo 8SPINE non supererebbero il challenge Cloudflare.
