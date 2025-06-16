# 描述(Description)
该容器提供Ascend 310B1 模型ATC转化的环境，由于Ascend 310B1 性能有限，直接在其上进行模型还换，速度非常慢。为了快速的进行模型转换，我们提供了X86 环境下的模型转换容器环境。 同时，我们安装AMCT 环境，用于模型的量化。

This container provides the environment for ATC model conversion of the Ascend 310B1. Due to the limited performance of the Ascend 310B1, direct model conversion on it is very slow. To enable faster model conversion, we offer a container environment for model conversion in an X86 setting. Additionally, we have installed the AMCT environment for model quantization.

# 使用步骤（Usage Instructions）
## Prerequisites
- docker environment

## Quick Start
1. Pull the Docker image:
```bash
docker pull harbor.edgesync.cloud/xian-embedded/ascend-cann-tookit-env:8.0.0
```

2. Run the container interactively

```bash
docker run  -it ascend-cann-tookit-env:8.0.0 /bin/bash
```
Now you can use it.
