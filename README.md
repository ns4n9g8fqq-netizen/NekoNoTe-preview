# NekoNoTe 가중치

[NekoNoTe](https://github.com/ns4n9g8fqq-netizen/NekoNoTe) 가 쓰는 모델 가중치 배포용 저장소입니다.
플러그인이 자동으로 받아가므로 직접 내려받을 일은 없습니다.

## 출처 및 라이선스

아래 모델들의 원저작자에게 감사드립니다. 각 라이선스 조건을 따릅니다.

### Apache-2.0

- **Meta SAM2** — `models/sam2-onnx/config.json`, `models/sam2-onnx/image_encoder.onnx`, `models/sam2-onnx/mask_decoder.onnx`
- **baberu-ocr** — `models/baberu-ocr/config.json`, `models/baberu-ocr/generation_config.json`, `models/baberu-ocr/onnx/decoder_prefill_int8.onnx`, `models/baberu-ocr/onnx/decoder_step_int8.onnx` 외 4개
- **huyvux3005/manga109-segmentation-bubble (HuggingFace)** — `weights/bubble_shape.onnx`
- **ogkalu/comic-text-and-bubble-detector (RT-DETR-v2 r50vd)** — `models/rtdetr-bubble-onnx/config.json`, `models/rtdetr-bubble-onnx/model.onnx`, `models/rtdetr-bubble-onnx/preprocessor_config.json`

### BSD-3-Clause

- **xinntao/Real-ESRGAN** — `weights/restore/onnx/4x_RealESRGAN_anime_6B.onnx`

### CC BY 4.0

- **OpenModelDB** — `weights/restore/onnx/4x-DWTP-DS-dat2-v3.onnx`

### CC BY-NC 4.0

- **Sirosky/Upscale-Hub — https://github.com/Sirosky/Upscale-Hub** — `weights/restore/onnx/2x_AniScale2_ESRGAN_i16_110K.onnx`
- **the-database/IllustrationJaNai** — `weights/restore/onnx/1x_IllustrationJaNai-DeJPEG_FDAT_M_100k.onnx`, `weights/restore/onnx/2x_IllustrationJaNai-DeJPEG_FDAT_M_100k.onnx`, `weights/restore/onnx/2x_IllustrationJaNai_V3denoise_FDAT_M_unshuffle_30k_fp16.onnx`, `weights/restore/onnx/2x_IllustrationJaNai_V3denoise_SPAN_S_30k_fp16.onnx` 외 3개
- **the-database/MangaJaNai** — `weights/restore/onnx/2x_MangaJaNai_1200p_V1_ESRGAN_70k.onnx`, `weights/restore/onnx/2x_MangaJaNai_1300p_V1_ESRGAN_75k.onnx`, `weights/restore/onnx/2x_MangaJaNai_1400p_V1_ESRGAN_70k.onnx`, `weights/restore/onnx/2x_MangaJaNai_1500p_V1_ESRGAN_90k.onnx` 외 3개

### CC BY-NC-SA 4.0

- **eula#9756 (OpenModelDB)** — `weights/restore/onnx/4x-eula-digimanga-bw-v2-nc1.onnx`

### GPL-3.0

- **Kiteretsu77/APISR — https://github.com/Kiteretsu77/APISR** — `weights/restore/onnx/2x_APISR_RRDB_GAN_generator.onnx`, `weights/restore/onnx/4x_APISR_DAT_GAN_generator.onnx`
- **dmMaze/comic-text-detector** — `vendor/comic-text-detector/data/comictextdetector.pt.onnx`

### MIT

- **JeffersonQin/YuzuMarker.FontDetection — https://github.com/JeffersonQin/YuzuMarker.FontDetection** — `weights/yuzumarker-font-detection.onnx`, `weights/yuzumarker-font-labels.json`
- **ShadowB/Manga109-panel-balloon-text-yolov26-segmentation (HuggingFace)** — `weights/manga_yolo.onnx`
- **bilibili/ailab Real-CUGAN — https://github.com/bilibili/ailab/tree/main/Real-CUGAN** — `weights/restore/onnx/2x_RealCUGAN_conservative.onnx`, `weights/restore/onnx/2x_RealCUGAN_denoise1x.onnx`, `weights/restore/onnx/2x_RealCUGAN_denoise2x.onnx`, `weights/restore/onnx/2x_RealCUGAN_denoise3x.onnx` 외 1개
- **clovaai/CRAFT-pytorch** — `weights/craft_mlt_25k.onnx`
- **intfloat/multilingual-e5-base — https://huggingface.co/intfloat/multilingual-e5-base** — `weights/e5-base/model_quantized.onnx`, `weights/e5-base/tokenizer.json`, `weights/e5-base/tokenizer_config.json`
- **mayocream/lama-manga — https://huggingface.co/mayocream/lama-manga** — `weights/lama_large_512px.onnx`
- **nagadomi/nunif (waifu2x)** — `weights/restore/w2x_swin_artscan_noise0_scale2x.onnx`, `weights/restore/w2x_swin_artscan_noise1_scale2x.onnx`, `weights/restore/w2x_swin_artscan_noise2_scale2x.onnx`, `weights/restore/w2x_swin_artscan_noise3_scale2x.onnx` 외 1개

### MIT / CC BY 4.0(주석)

- **ku21fan/COO (Manga109 이미지 기반)** — `weights/coo_link_prior.json`, `weights/coo_trba_2d.onnx`

### 표기 없음

- **a-b-c-x-y-z/Manga-Text-Segmentation-2025 — https://huggingface.co/a-b-c-x-y-z/Manga-Text-Segmentation-2025** — `weights/manga-text-segmentation-2025/model.onnx`
- **deepghs/manga109_yolo (HuggingFace) — https://huggingface.co/deepghs/manga109_yolo** — `weights/manga109_det.onnx`
- **sudo (OpenModelDB) — https://openmodeldb.info/models/2x-sudo-shuffle-cugan-9-584-969** — `weights/restore/onnx/2x_sudo_shuffle_cugan_9.584.969.onnx`
- **umzi (OpenModelDB) — https://openmodeldb.info/models/1x-wtp-descreentone-compact** — `weights/restore/onnx/1x_wtp_descreenton_compact.onnx`

## 비상업 이용 안내

CC BY-NC / CC BY-NC-SA 로 배포되는 모델이 포함되어 있습니다.
이 가중치를 쓴 결과물을 **상업적으로 이용할 수 없습니다.**


---

이 목록은 실제 배포 파일 목록에서 자동 생성됩니다. 빠진 출처가 있으면 알려주세요.
