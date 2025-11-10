# LLM Benchmark Results

**Generated:** 2025-10-30 20:10:16

## System Information

- **Hostname:** home-tower
- **OS:** Linux 6.8.0-58-generic
- **Python:** 3.12.3
- **Ollama:** 0.12.6
- **CPU:** AMD Ryzen 5 3600 6-Core Processor (12 cores)
- **RAM:** 31.3 GB
- **GPU:** Not available (CPU only)

---

## Summary

| Model | Prompt Eval (t/s) | Response (t/s) | Total (t/s) | Avg Prompt Tokens | Avg Response Tokens |
|-------|-------------------|----------------|-------------|-------------------|---------------------|
| hf.co/unsloth/DeepSeek-R1-0528-Qwen3-8B-GGUF:Q4_K_XL | 141.68 | 7.41 | 7.54 | 43 | 2034 |
| qwen3:4b | 286.07 | 10.58 | 10.72 | 55 | 3755 |

---

## Detailed Results

### hf.co/unsloth/DeepSeek-R1-0528-Qwen3-8B-GGUF:Q4_K_XL

**Average Performance:**

```
Prompt eval: 141.68 t/s
Response: 7.41 t/s
Total: 7.54 t/s

Stats:
  Prompt tokens: 43
  Response tokens: 2034
  Model load time: 0.15s
  Prompt eval time: 1.06s
  Response time: 275.48s
  Total time: 277.48s
```

**Individual Runs:**

1. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 7.66 t/s, 1503 tokens, 198.09s
2. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 7.55 t/s, 1746 tokens, 232.25s
3. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 7.40 t/s, 2059 tokens, 280.99s
4. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 7.40 t/s, 2036 tokens, 276.13s
5. ✗ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Error: Timeout after 600s (model may still be generating)
6. ✗ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Error: Timeout after 600s (model may still be generating)
7. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 7.16 t/s, 2613 tokens, 368.05s
8. ✗ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Error: Timeout after 600s (model may still be generating)
9. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 7.36 t/s, 2134 tokens, 293.19s
10. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 7.35 t/s, 2150 tokens, 293.68s

### qwen3:4b

**Average Performance:**

```
Prompt eval: 286.07 t/s
Response: 10.58 t/s
Total: 10.72 t/s

Stats:
  Prompt tokens: 55
  Response tokens: 3755
  Model load time: 0.14s
  Prompt eval time: 0.77s
  Response time: 364.19s
  Total time: 366.59s
```

**Individual Runs:**

1. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 11.08 t/s, 2795 tokens, 254.18s
2. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 10.43 t/s, 3414 tokens, 328.97s
3. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 10.70 t/s, 3350 tokens, 315.62s
4. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 11.78 t/s, 2464 tokens, 210.44s
5. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 9.62 t/s, 5439 tokens, 569.18s
6. ✗ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Error: Timeout after 600s (model may still be generating)
7. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 9.57 t/s, 5631 tokens, 591.74s
8. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 9.80 t/s, 4927 tokens, 505.99s
9. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 11.19 t/s, 2815 tokens, 254.00s
10. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 11.04 t/s, 2959 tokens, 269.24s

