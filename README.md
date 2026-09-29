# MiniMax H3 Characters LoRA

The three character LoRAs selected by the owner are distributed as GitHub Release assets.

| Character | Trigger | Epochs | Steps | Asset |
| --- | --- | ---: | ---: | --- |
| Mark | `m4rk_person` | 80 | 1760 | `mark_h3_80e.safetensors` |
| Nicole | `n1cole_person` | 60 | 1500 | `nicole_h3_60e.safetensors` |
| Melisa | `m3lisa_person` | 80 | 2000 | `melisa_h3_80e.safetensors` |

[MiniMax H3 Characters LoRA v1](https://github.com/sergejmamantov5-wq/12/releases/tag/h3-characters-v1)

Nicole is the explicitly selected `nicole_h3_fizgig_v1_20260928_224102.safetensors` checkpoint.
The release manifest records original filenames, exact sizes and SHA-256 checksums.

## Download on a Vast AI instance

Run this single command:

```bash
curl -fL --retry 3 https://github.com/sergejmamantov5-wq/12/releases/download/h3-characters-v1/download_h3_characters.sh -o /tmp/download_h3_characters.sh && bash /tmp/download_h3_characters.sh
```

The script installs aria2 on Ubuntu/Debian if needed, downloads into `/workspace/ComfyUI/models/loras/`, resumes interrupted transfers and verifies every file with SHA-256. A checksum mismatch exits with an error. Already verified files are skipped.

All three release assets were downloaded back and matched the original local SHA-256 checksums. The download script was also tested in Ubuntu.
