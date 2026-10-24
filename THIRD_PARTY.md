# Сторонние компоненты

«Сказано» распространяется бесплатно в виде установщика. Внутри и при первом
запуске используются компоненты других авторов. Спасибо им.

## Модели

| Компонент | Автор | Лицензия |
|---|---|---|
| Whisper large-v3-turbo (веса модели) | OpenAI | MIT |
| [mlx-community/whisper-large-v3-turbo-q4](https://huggingface.co/mlx-community/whisper-large-v3-turbo-q4) — версия для Apple Silicon | MLX Community | MIT |
| [mobiuslabsgmbh/faster-whisper-large-v3-turbo](https://huggingface.co/mobiuslabsgmbh/faster-whisper-large-v3-turbo) — версия для Intel | Mobius Labs | MIT |
| Opus-MT tc-big zle-en — перевод на английский на macOS 13–14 | Helsinki-NLP, Tatoeba Translation Challenge | CC BY 4.0 |
| [luigi000/opus-mt-tc-big-zle-en-ct2-int8](https://huggingface.co/luigi000/opus-mt-tc-big-zle-en-ct2-int8) — сжатая версия той же модели | luigi000 | CC BY 4.0 |

## Библиотеки

| Компонент | Лицензия |
|---|---|
| Python (сборка python-build-standalone) | PSF License |
| MLX, mlx-whisper (Apple Silicon) | MIT |
| CTranslate2, faster-whisper (Intel и перевод) | MIT |
| PyObjC | MIT |
| rumps | BSD-3-Clause |
| NumPy, SciPy | BSD-3-Clause |
| PyAV (Intel) — внутри библиотеки FFmpeg | BSD-3-Clause; FFmpeg — LGPL 2.1 или новее |
| SentencePiece, tokenizers, huggingface_hub, requests | Apache 2.0 |
| tiktoken | MIT |

Полные тексты лицензий библиотек лежат внутри приложения, в папках
`Сказано.app/Contents/Resources/python/lib/python3.12/site-packages/*.dist-info/licenses/`.
Исходный код FFmpeg доступен на https://ffmpeg.org.
