# cheetah-rs

Testing pico voice cheetah.

# Requirements

- Sign up on picovoice and get an AccessKey.

# Build

```bash
$ cargo build --release
```

# Run

File mode:

```
$ ./target/release/pv_cheeetah_filemode --access_key <Your_Access_Key> --input_audio_path <Your_Audio_file>
```

Mic mode:

```
$ ./target/release/pv_cheeetah_micmode --access_key <Your_Access_Key>
```
