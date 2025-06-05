# Nvidia Cosmos

Cosmos World Foundation Models come in three model types which can all be customized in post-training: [cosmos-predict](https://github.com/nvidia-cosmos/cosmos-predict1), [cosmos-transfer](https://github.com/nvidia-cosmos/cosmos-transfer1), and [cosmos-reason](https://github.com/nvidia-cosmos/cosmos-reason1):

|  | Predict | Transfer | Reason |
| ----- | :---: | :---: | :---: |
| **Type** | World Generation | Multi-Controlnet | Reasoning VLM |
| **Function** | Predict novel future frames given initial frames  | Transfer existing control frames into photoreal frames within a video clip | Reason against frames within a video clip |
| **Use Cases** | Data Generation & Policy Evaluation | Data Augmentation | Data Curation |
| **Inputs** | Text, Image, Video  | Multiple Video Modalities such as RGB, Depth, Segmentation, and more. | Video & Text |
| **Outputs** | Video | Video | Text  |

# 

# Use Cases in Physical AI Development

Our world foundation models are purpose-built to accelerate improving performance in downstream model tasks in various stages, as illustrated here in the flywheel.

![Cosmos Data Flywheel](https://private-user-images.githubusercontent.com/6860749/452096962-8df6bc0c-2ba7-4bd1-9d1c-cc8279f8daf3.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDkxNjUxOTUsIm5iZiI6MTc0OTE2NDg5NSwicGF0aCI6Ii82ODYwNzQ5LzQ1MjA5Njk2Mi04ZGY2YmMwYy0yYmE3LTRiZDEtOWQxYy1jYzgyNzlmOGRhZjMuanBnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI1MDYwNSUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNTA2MDVUMjMwODE1WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NWJjMjdhZjZlOGU4MmQzOTM4ZGMzMTVjZmM0N2NiM2VmMjRiN2MxMzJjNmM2ZmVkMmJlYmQ2ODIxMGYwYmJlYiZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.xeaFQQljBsAJcWtCdaT-1uIovsZxJavdAMhokW6Pkwk)
