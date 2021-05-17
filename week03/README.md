Our lecture (video) - https://disk.yandex.ru/i/8Fx5f4ewhGLeWA

References:
* PyTorch gradient checkpointing - [API reference](https://pytorch.org/docs/stable/checkpoint.html)
* GPipe (one good implementation of pipelining) - [arxiv](https://arxiv.org/abs/1811.06965)
* DeepSpeed (a library of many tricks) - [repo](https://github.com/microsoft/DeepSpeed)
    * Parameter/Optimizer State Sharding in ZeRO - [arxiv](https://arxiv.org/pdf/1910.02054v3.pdf) [blog](https://www.microsoft.com/en-us/research/blog/zero-deepspeed-new-system-optimizations-enable-training-models-with-over-100-billion-parameters/)
    * ZeRO-offload - moving gradients and statistics from GPU into RAM - [arxiv](https://arxiv.org/abs/2101.06840) [blog](https://www.deepspeed.ai/news/2021/03/07/zero3-offload.html)
* FairScale - sharded DDP and pipeline with humane API - [repo](https://github.com/facebookresearch/fairscale)
* Megatron-LM - one honking great implementation of large-scale training for transformers - [repo](https://github.com/NVIDIA/Megatron-LM)
