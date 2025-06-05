
<!-- ![llm-kv-cache](https://github.com/Zefan-Cai/Awesome-LLM-KV-Cache/assets/31974251/4d9ab775-f200-471d-a289-e2b14296b633) -->

<!-- <div align='center'>
  <img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg >
  <img src=https://img.shields.io/github/downloads/Zefan-Cai/Awesome-LLM-KV-Cache/total?color=ccf&label=downloads&logo=github&logoColor=lightgrey >
  <img src=https://img.shields.io/github/forks/Zefan-Cai/Awesome-LLM-KV-Cache.svg?style=social >
  <img src=https://img.shields.io/github/stars/Zefan-Cai/Awesome-LLM-KV-Cache.svg?style=social >
  <img src=https://img.shields.io/github/watchers/Zefan-Cai/Awesome-LLM-KV-Cache.svg?style=social >
  <img src=https://img.shields.io/badge/Release-v1.6-brightgreen.svg >
  <img src=https://img.shields.io/badge/License-GPLv3.0-turquoise.svg >
 </div>    -->

## 📒Introduction
Awesome-LLM-KV-Cache: A curated list of [📙Awesome LLM KV Cache Papers with Codes](#paperlist). This repository is for personal use of learning and classifying the burning KV Cache related papers!

## ©️Citations 


## 📖Contents 
<div id="paperlist"></div>

* 📖[Trending Inference Topics](#Trending-Inference-Topics)🔥🔥🔥
* 📖[KV Cache Compression](#KV-Cache-Compression)🔥🔥
* 📖[KV Cache Merge](#KV-Cache-Merge)🔥🔥
* 📖[Budget Allocation](#Budget-Allocation)🔥
* 📖[Cross-Layer KV Cache Utilization](#Cross-Layer-KV-Cache-Utilization)🔥
* 📖[KV Cache Quantization](#KV-Cache-Quantization)🔥
* 📖[Low-Rank KV Cache Decomposition](#Low-Rank-KV-Cache-Decomposition)🔥
* 📖[Observation](#Observation)🔥🔥
* 📖[Evaluation](#Evaluation)🔥
* 📖[Systems](#Systems)
* 📖[Others](#Others)

### 📖Trending Inference Topics ([©️back👆🏻](#paperlist))  
<div id="Trending-Inference-Topics"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.05| 🔥🔥🔥[DeepSeek-V2] DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model(@DeepSeek-AI)|[[pdf]](https://arxiv.org/pdf/2405.04434) | [[DeepSeek-V2]](https://github.com/deepseek-ai/DeepSeek-V2) ![](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2.svg?style=social)| ⭐️⭐️⭐️ | 
|2024.05|🔥🔥🔥[YOCO] You Only Cache Once: Decoder-Decoder Architectures for Language Models(@Microsoft)| [[pdf]](https://arxiv.org/pdf/2405.05254) | [[unilm-YOCO]](https://github.com/microsoft/unilm/tree/master/YOCO) ![](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social) |⭐️⭐️⭐️ |  
|2024.06|🔥🔥[**Mooncake**] Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving(@Moonshot AI) |[[pdf]](https://github.com/kvcache-ai/Mooncake/blob/main/Mooncake-v1.pdf) | [[Mooncake]](https://github.com/kvcache-ai/Mooncake) ![](https://img.shields.io/github/stars/kvcache-ai/Mooncake.svg?style=social)|⭐️⭐️⭐️ |    
|2024.07|🔥🔥🔥[**FlashAttention-3**] FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision(@TriDao etc) |[[pdf]](https://tridao.me/publications/flash3/flash3.pdf)|[[flash-attention]](https://github.com/Dao-AILab/flash-attention) ![](https://img.shields.io/github/stars/Dao-AILab/flash-attention.svg?style=social)|⭐️⭐️⭐️ |  
|2024.07|🔥🔥🔥[**MInference 1.0**] MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention(@Microsoft) |[[pdf]](https://arxiv.org/pdf/2407.02490)|[[MInference 1.0]](https://github.com/microsoft/MInference) ![](https://img.shields.io/github/stars/microsoft/MInference.svg?style=social)|⭐️⭐️⭐️ |

### LLM KV Cache Compression ([©️back👆🏻](#paperlist))
<div id="#KV-Cache-Compression"></div>

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2023.06| 🔥🔥[**H2O**] H2O: Heavy-Hitter Oracle for Efficient Generative Inference of Large Language Models|[[pdf]](https://arxiv.org/abs/2306.14048) | [[H2O]](https://github.com/FMInference/H2O) ![](https://img.shields.io/github/stars/FMInference/H2O.svg?style=social)| ⭐️⭐️⭐️ |Attention-based selection|
|2023.09| 🔥🔥🔥[**StreamingLLM**] Efficient Streaming Language Models with Attention Sinks|[[pdf]](https://arxiv.org/abs/2309.17453) | [[streaming-llm]](https://github.com/mit-han-lab/streaming-llm) ![](https://img.shields.io/github/stars/mit-han-lab/streaming-llm.svg?style=social)| ⭐️⭐️⭐️ |Retain first few tokens|
|2023.10| 🔥[**FastGen**] Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs|[[pdf]](https://arxiv.org/abs/2310.01801) | | ⭐️⭐️ |Head-specific compression strategies|
|2023.10| 🔥🔥[**CacheGen**] KV Cache Compression and Streaming for Fast Large Language Model Serving|[[pdf]](https://arxiv.org/abs/2310.07240) | [[LMCache]](https://github.com/LMCache/LMCache) ![](https://img.shields.io/github/stars/LMCache/LMCache.svg?style=social) | ⭐️⭐️⭐️ |Compress KV cache to bitstreams for storage and sharing|
|2024.04| 🔥🔥[**SnapKV**] SnapKV: LLM Knows What You are Looking for Before Generation|[[pdf]](https://arxiv.org/abs/2404.14469) | [[SnapKV]](https://github.com/FasterDecoding/SnapKV) ![](https://img.shields.io/github/stars/FasterDecoding/SnapKV.svg?style=social)| ⭐️⭐️⭐️ |Attention Pooling before selection|
|2024.05| [**Scissorhands**] Scissorhands: Exploiting the Persistence of Importance Hypothesis for LLM KV Cache Compression at Test Time|[[pdf]](https://arxiv.org/abs/2305.17118) | | ⭐️ ||
|2024.06| 🔥A Simple and Effective L2 Norm-Based Strategy for KV Cache Compression|[[pdf]](https://arxiv.org/abs/2406.11430) | | ⭐️ |L2 Norm is better than attention as a metrics||
|2024.06| CORM: Cache Optimization with Recent Message for Large Language Model Inference|[[pdf]](https://arxiv.org/pdf/2404.15949) | | ⭐️ |||
|2024.07| Efficient Sparse Attention needs Adaptive Token Release|[[pdf]](https://arxiv.org/abs/2407.02328) | | ⭐️ ||
|2024.03| [**ALISA**] ALISA: Accelerating Large Language Model Inference via Sparsity-Aware KV Caching|[[pdf]](https://arxiv.org/abs/2403.17312) | | ⭐️ |
|2024.03| 🔥🔥🔥[**FastV**] Code for paper: An Image is Worth 1/2 Tokens After Layer 2: Plug-and-Play Inference Acceleration for Large Vision-Language Models|[[pdf]](https://arxiv.org/abs/2403.06764) | [[EasyKV]](https://github.com/pkunlp-icler/FastV) ![](https://img.shields.io/github/stars/pkunlp-icler/FastV.svg?style=social)| ⭐️⭐️⭐️ |
|2024.03| [**Keyformer**] Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference|[[pdf]](https://arxiv.org/abs/2403.09054) | [[keyformer-llm]](https://github.com/d-matrix-ai/keyformer-llm) ![](https://img.shields.io/github/stars/d-matrix-ai/keyformer-llm.svg?style=social)| ⭐️⭐️ |
|2024.06| Effectively Compress KV Heads for LLM |[[pdf]](https://arxiv.org/abs/2406.07056) | | ⭐️ |
|2024.06| 🔥 Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters|[[pdf]](https://arxiv.org/abs/2406.12335) | | ⭐️ |
|2024.06|  On the Efficacy of Eviction Policy for Key-Value Constrained Generative Language Model Inference|[[pdf]](https://arxiv.org/abs/2402.06262) | [[EasyKV]](https://github.com/DRSY/EasyKV) ![](https://img.shields.io/github/stars/DRSY/EasyKV.svg?style=social)| ⭐️ |
|2025.05| 🔥[**KVzip**] KVzip: Query-Agnostic KV Cache Compression with Context Reconstruction |[[pdf]](https://arxiv.org/abs/2505.23416) | [[KVzip]](https://github.com/snu-mllab/KVzip) ![](https://img.shields.io/github/stars/snu-mllab/KVzip.svg?style=social)| ⭐️⭐️ |



### KV Cache Merge ([©️back👆🏻](#paperlist))
<div id="KV-Cache-Merge"></div>

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2025.02| 🔥[**CacheCraft**] Cache-Craft: Managing Chunk-Caches for Efficient Retrieval-Augmented Generation |[[pdf]](https://www.arxiv.org/pdf/2502.15734) | | |Reducing Redundant KV Computation in RAG via Chunked Caching|
|2023.10| 🔥🔥[**CacheBlend**] Fast Large Language Model Serving for RAG with Cached Knowledge Fusion|[[pdf]](https://arxiv.org/abs/2405.16444) | [[LMCache]](https://github.com/LMCache/LMCache) ![](https://img.shields.io/github/stars/LMCache/LMCache.svg?style=social) | ⭐️⭐️⭐️ |Selective update when merging KV caches|
|2023.12| 🔥 Compressed Context Memory For Online Language Model Interaction|[[pdf]](https://arxiv.org/pdf/2312.03414) | [[ContextMemory]](https://github.com/snu-mllab/Context-Memory) ![](https://img.shields.io/github/stars/snu-mllab/Context-Memory.svg?style=social) | ⭐️⭐️⭐️ |Finetuning LLMs to recurrently compress KV caches|
|2024.01| [**CaM**] CaM: Cache Merging for Memory-efficient LLMs Inference|[[pdf]](https://openreview.net/forum?id=LCTmppB165) | [[cam]](https://github.com/zyxxmu/cam) ![](https://img.shields.io/github/stars/zyxxmu/cam.svg?style=social)| ⭐️⭐️ |
|2024.05| 🔥🔥 You Only Cache Once: Decoder-Decoder Architectures for Language Models|[[pdf]](https://arxiv.org/abs/2405.05254) | [[unilm]](https://github.com/microsoft/unilm) ![](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social)| ⭐️⭐️ |
|2024.06| 🔥🔥[**D2O**] D2O: Dynamic Discriminative Operations for Efficient Generative Inference of Large Language Models|[[pdf]](https://arxiv.org/abs/2406.13035) | | ⭐️⭐️⭐️ |
|2024.07| 🔥 [**KVMerger**]Model Tells You Where to Merge: Adaptive KV Cache Merging for LLMs on Long-Context Tasks|[[pdf]](https://arxiv.org/abs/2407.08454) | | ⭐️⭐️⭐️ |

### Budget Allocation ([©️back👆🏻](#paperlist))
<div id="Budget-Allocation"></div>

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.05| 🔥[**PyramidInfer**] PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference|[[pdf]](https://arxiv.org/abs/2405.12532) | [[PyramidInfer]](https://github.com/mutonix/pyramidinfer) ![](https://img.shields.io/github/stars/mutonix/pyramidinfer.svg?style=social)| ⭐️⭐️⭐️ |Layer-wise budget allocation|
|2024.06| 🔥[**PyramidKV**] PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling|[[pdf]](https://arxiv.org/abs/2406.02069) | [[PyramidKV]](https://github.com/Zefan-Cai/PyramidKV) ![](https://img.shields.io/github/stars/Zefan-Cai/PyramidKV.svg?style=social)| ⭐️⭐️⭐️ |Layer-wise budget allocation|
|2024.07| 🔥[**Ada-KV**] Ada-KV: Optimizing KV Cache Eviction by Adaptive Budget Allocation for Efficient LLM Inference|[[pdf]](https://arxiv.org/abs/2407.11550) | | ⭐️⭐️⭐️ |Head-wise budget allocation|
|2024.07|  RazorAttention: Efficient KV Cache Compression Through Retrieval Heads|[[pdf]](https://arxiv.org/pdf/2407.15891) | | ⭐️ |

### Cross-Layer KV Cache Utilization ([©️back👆🏻](#paperlist))
<div id="Cross-Layer-KV-Cache-Utilization"></div>

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.05| 🔥 Reducing Transformer Key-Value Cache Size with Cross-Layer Attention|[[pdf]](https://arxiv.org/abs/2405.12981) | | ⭐️ ||
|2024.05| 🔥 Layer-Condensed KV Cache for Efficient Inference of Large Language Models|[[pdf]](https://arxiv.org/abs/2405.10637) | [[**LCKV**]](https://github.com/whyNLP/LCKV) ![](https://img.shields.io/github/stars/whyNLP/LCKV.svg?style=social)| ⭐️⭐️ ||
|2024.05| 🔥🔥🔥[**MiniCache**] MiniCache: KV Cache Compression in Depth Dimension for Large Language Models|[[pdf]](https://arxiv.org/abs/2405.14366) | | ⭐️⭐️⭐️ ||
|2024.06| 🔥[**MLKV**] MLKV: Multi-Layer Key-Value Heads for Memory Efficient Transformer Decoding|[[pdf]](https://arxiv.org/abs/2406.09297) | [[pythia-mlkv]](https://github.com/zaydzuhri/pythia-mlkv) ![](https://img.shields.io/github/stars/zaydzuhri/pythia-mlkv.svg?style=social)| ⭐️⭐️ ||

### KV Cache Quantization ([©️back👆🏻](#paperlist))  
<div id="KV-Cache-Quantization"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2023.03| 🔥[**GEAR**] GEAR: An Efficient KV Cache Compression Recipe for Near-Lossless Generative Inference of LLM|[[pdf]](https://arxiv.org/abs/203.05527) | [[GEAR]](https://github.com/opengear-project/GEAR) ![](https://img.shields.io/github/stars/opengear-project/GEAR.svg?style=social)| ⭐️⭐️ ||
|2024.01| 🔥🔥[**KVQuant**] KVQuant: Towards 10 Million Context Length LLM Inference with KV Cache Quantization|[[pdf]](https://arxiv.org/abs/2401.18079) | [[KVQuant]](https://github.com/SqueezeAILab/KVQuant) ![](https://img.shields.io/github/stars/SqueezeAILab/KVQuant.svg?style=social)| ⭐️⭐️ |Make all KV cache quantized|
|2024.02| [No Token Left Behind] No Token Left Behind: Reliable KV Cache Compression via Importance-Aware Mixed Precision Quantization|[[pdf]](https://arxiv.org/abs/2402.18096) | | ⭐️⭐️⭐️ ||
|2024.02| [**KIVI**] KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache|[[pdf]](https://arxiv.org/abs/2402.02750) | [[KIVI]](https://github.com/jy-yuan/KIVI) ![](https://img.shields.io/github/stars/jy-yuan/KIVI.svg?style=social)| ⭐️⭐️ ||
|2024.02| [**WKVQuant**] WKVQuant: Quantizing Weight and Key/Value Cache for Large Language Models Gains More|[[pdf]](https://arxiv.org/pdf/2402.12065) ||||
|2024.03| [**QAQ**] QAQ: Quality Adaptive Quantization for LLM KV Cache|[[pdf]](https://arxiv.org/abs/2403.04643) | [[QAQ-KVCacheQuantization]](https://github.com/ClubieDong/QAQ-KVCacheQuantization) ![](https://img.shields.io/github/stars/ClubieDong/QAQ-KVCacheQuantization.svg?style=social)| ⭐️ |attention-based KV cache quantized|
|2024.05| [**ZipCache**] ZipCache: Accurate and Efficient KV Cache Quantization with Salient Token Identification|[[pdf]](https://www.arxiv.org/abs/2405.14256) | | ⭐️ ||
|2024.05|  Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression|[[pdf]](https://arxiv.org/abs/2405.12591) | | ⭐️ ||
|2024.05| [**SKVQ**] SKVQ: Sliding-window Key and Value Cache Quantization for Large Language Models|[[pdf]](https://arxiv.org/abs/2405.06219) | [[SKVQ]](https://github.com/cat538/SKVQ) ![](https://img.shields.io/github/stars/cat538/SKVQ.svg?style=social)| ⭐️ |
|2024.07| [**PQCache**] PQCache: Product Quantization-based KVCache for Long Context LLM Inference|[[pdf]](https://arxiv.org/abs/2407.12820) | | ⭐️ ||


https://arxiv.org/abs/2402.12065
### Evaluation ([©️back👆🏻](#paperlist))  
<div id="Evaluation"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.07| 🔥[Benchmark] KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches|[[pdf]](https://arxiv.org/abs/2407.01527) | | ⭐️ ||

### Low Rank KV Cache Decomposition ([©️back👆🏻](#paperlist))  
<div id="Low-Rank-KV-Cache-Decomposition"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.02| Get More with LESS: Synthesizing Recurrence with KV Cache Compression for Efficient LLM Inference|[[pdf]](https://arxiv.org/abs/2402.09398) | [[LESS]](https://github.com/hdong920/LESS) ![](https://img.shields.io/github/stars/hdong920/LESS.svg?style=social)| ⭐️⭐️⭐️ |Fine-tune to make the KV cache low-ranked|
|2024.05| 🔥🔥🔥[**DeepSeek-V2**] DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model|[[pdf]](https://arxiv.org/abs/2405.04434) | [[DeepSeek-V2]](https://github.com/deepseek-ai/DeepSeek-V2) ![](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2.svg?style=social)| ⭐️⭐️⭐️ |Train low-rank KV cache from scratch|
|2024.06| [**Loki**] Loki: Low-Rank Keys for Efficient Sparse Attention|[[pdf]](https://arxiv.org/abs/2406.02542) | | ⭐️ ||

### Observation ([©️back👆🏻](#paperlist))  
<div id="Observation"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2022.09| In-context Learning and Induction Heads|[[pdf]](https://arxiv.org/abs/2209.11895) || ⭐️⭐️ |
|2024.01| 🔥Transformers are Multi-State RNNs|[[pdf]](https://arxiv.org/abs/2401.06104) | [[TOVA]](https://github.com/schwartz-lab-NLP/TOVA) ![](https://img.shields.io/github/stars/schwartz-lab-NLP/TOVA.svg?style=social)| ⭐️⭐️ |
|2024.04| 🔥[**Retrieval Head**] Retrieval Head Mechanistically Explains Long-Context Factuality|[[pdf]](https://arxiv.org/abs/2404.15574) | [[Retrieval_Head]](https://github.com/nightdessert/Retrieval_Head) ![](https://img.shields.io/github/stars/nightdessert/Retrieval_Head.svg?style=social)| ⭐️⭐️⭐️ ||
|2024.04| 🔥[**Massive Activations**] Massive Activations in Large Language Models|[[pdf]](https://arxiv.org/pdf/2402.17762) | [[Massive Activation]](https://github.com/locuslab/massive-activations) ![](https://img.shields.io/github/stars/locuslab/massive-activations.svg?style=social)| ⭐️⭐️⭐️ ||

### Systems ([©️back👆🏻](#paperlist))  
<div id="Systems"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.06|🔥🔥[**Mooncake**] Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving(@Moonshot AI) |[[pdf]](https://github.com/kvcache-ai/Mooncake/blob/main/Mooncake-v1.pdf) | [[Mooncake]](https://github.com/kvcache-ai/Mooncake) ![](https://img.shields.io/github/stars/kvcache-ai/Mooncake.svg?style=social)|⭐️⭐️⭐️ |    
|2024.02| MemServe: Context Caching for Disaggregated LLM Serving with Elastic Memory Pool |[[pdf]](https://arxiv.org/pdf/2406.17565) | | ⭐️ ||

### Others ([©️back👆🏻](#paperlist))  
<div id="Others"></div>  

|Date|Title|Paper|Code|Recom|Comment|
|:---:|:---:|:---:|:---:|:---:|:---:|
|2024.02| Effectively Compress KV Heads for LLM |[[pdf]](https://arxiv.org/pdf/2406.07056) | | ⭐️ ||
|2024.07| 🔥🔥Q-Sparse: All Large Language Models can be Fully Sparsely-Activated |[[pdf]](https://arxiv.org/abs/2407.10969) | [[GeneralAI]](https://aka.ms/GeneralAI) ![](https://img.shields.io/github/stars/microsoft/unilm.svg?style=social)| ⭐️⭐️⭐️ ||



## ©️License  

GNU General Public License v3.0  

## 🎉Contribute  

Welcome to star & submit a PR to this repo! 



```BibTeX
@misc{Awesome-LLM-Inference@2024,
  title={Awesome-LLM-KV-Cache: A curated list of Awesome LLM Inference Papers with codes},
  url={https://github.com/Zefan-Cai/Awesome-LLM-KV-Cache},
  note={Open-source software available at https://github.com/Zefan-Cai/Awesome-LLM-KV-Cache},
  author={Zefan-Cai, etc},
  year={2024}
}
```
