# 五、发布OpenAI 兼容服务器

```bash
vllm serve /root/autodl-tmp/moonshotai/Kimi-VL-A3B-Instruct --served-model-name kimi-vl --trust-remote-code --tensor-parallel-size 1 --max-num-batched-tokens 32768 --max-model-len 32768 --limit-mm-per-prompt image=8

```

