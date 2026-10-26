### Terminal Builds
Create/activate environment by running from project root:
```bash
source scripts/setup_build_env.sh
```

Build firmware on your local machine:
```bash
esphome compile firmware/esphome/5-audio-brick-s3/audio-brick-s3-idf.yaml
```

Upload firmware to your Core Board:
```bash
esphome upload firmware/esphome/5-audio-brick-s3/audio-brick-s3-idf.yaml
```

Tail the ESPHome logs:
```bash
esphome logs firmware/esphome/5-audio-brick-s3/audio-brick-s3-idf.yaml
```