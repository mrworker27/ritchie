# ritchie

## How to install

Just run script
```bash
./install.sh
```

## Extract subtitles

If you have a single subtitle track
```bash
input_file=example.mkv output_file=subs.srt ritchie extract_subs
```

You can specify subtitle track by number (if multiple present). NOTE: zero-based mapping
```bash
input_file=example.mkv output_file=subs.srt subtitle=1 ritchie extract_subs
```

## Burn subtitles

If you have both single subtitle & audio track
```bash
input_file=example.mkv ritchie burn_subs
```

You can specify subtitle or/and audio track by number (if multiple present). NOTE: zero-based mapping
```bash
input_file=example.mkv subtitle=1 audio=1 ritchie burn_subs
```
