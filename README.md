# Articles

The code, data and figures behind the articles on [blog.korolevalab.com](https://blog.korolevalab.com), one folder per article. A folder
holds the text as it went to the site (`post.md`), the scripts that measure, simulate or download what the article
reports, the data they produced, and `figures.py`, which draws the figures from that data. Six of the articles are
also deposited on Zenodo with a DOI.

| Folder | Article |
|---|---|
| [`adapters`](adapters) | [Parameter-efficient fine-tuning in PyTorch: adapters, LoRA and the rest](https://blog.korolevalab.com/blog/2025/adapters/) |
| [`brain_ai`](brain_ai) | [How similar is the human brain to AI models?](https://blog.korolevalab.com/blog/2026/brain-and-ai-models/) |
| [`centaur`](centaur) | [Is Centaur a model of the mind? An LLM fine-tuned on 160 psychology experiments](https://blog.korolevalab.com/blog/2026/centaur/) · [DOI](https://doi.org/10.5281/zenodo.24114953) |
| [`consciousness`](consciousness) | [Theories of consciousness and the hard problem](https://blog.korolevalab.com/blog/2026/theories-of-consciousness/) |
| [`creative_ai`](creative_ai) | [Can AI be creative?](https://blog.korolevalab.com/blog/2025/creative-ai/) |
| [`crypto_trading`](crypto_trading) | [AI crypto trading bots: what machine learning and LLMs can and can't do](https://blog.korolevalab.com/blog/2026/ai-crypto-trading/) · [DOI](https://doi.org/10.5281/zenodo.24114945) |
| [`damasio`](damasio) | [Damasio's somatic marker hypothesis: the body in decision-making](https://blog.korolevalab.com/blog/2025/antonio-damasio/) |
| [`friston`](friston) | [How Karl Friston's free energy principle works and what its critics say](https://blog.korolevalab.com/blog/2026/free-energy-principle/) |
| [`game_theory`](game_theory) | [Is it rational to be good? Game theory and the ethics of cooperation](https://blog.korolevalab.com/blog/2026/game-theory-ethics/) |
| [`hybrid_attention`](hybrid_attention) | [Hybrid attention: why new LLMs keep full attention in only a few layers](https://blog.korolevalab.com/blog/2026/hybrid-attention/) · [DOI](https://doi.org/10.5281/zenodo.24114949) |
| [`inference_optimization`](inference_optimization) | [LLM inference optimization: where the time and memory go](https://blog.korolevalab.com/blog/2025/inference-optimization/) · [DOI](https://doi.org/10.5281/zenodo.24114957) |
| [`llms_intro`](llms_intro) | [How large language models work, for those who missed out](https://blog.korolevalab.com/blog/2024/llms-for-those-who-missed-out/) |
| [`lora`](lora) | [The algebra of LoRA: how low-rank adaptation works](https://blog.korolevalab.com/blog/2024/lora-algorithm-for-llms/) |
| [`minds_as_computers`](minds_as_computers) | [Is the mind a computer? The computational theory of mind](https://blog.korolevalab.com/blog/2025/minds-as-computers/) |
| [`moe`](moe) | [Mixture of experts: why the largest LLMs use a few percent of their weights per token](https://blog.korolevalab.com/blog/2026/mixture-of-experts/) · [DOI](https://doi.org/10.5281/zenodo.24114947) |
| [`polymarket`](polymarket) | [How accurate is Polymarket? Calibration, longshot bias and a volume trap](https://blog.korolevalab.com/blog/2026/polymarket-accuracy/) · [DOI](https://doi.org/10.5281/zenodo.24114942) |

The case studies of the [portfolio](https://blog.korolevalab.com/portfolio/) are built the same way:

| Folder | Case study |
|---|---|
| [`cashierless_store`](cashierless_store) | [Cashierless Store](https://blog.korolevalab.com/projects/cashierless-store/) |
| [`fashion_tryon`](fashion_tryon) | [AI Fashion App](https://blog.korolevalab.com/projects/ai-fashion-virtual-try-on-app/) |
| [`floorplan`](floorplan) | [3D Floorplan Reconstruction](https://blog.korolevalab.com/projects/3d-floorplan-reconstruction/) |
| [`medical_assistant`](medical_assistant) | [Medical Assistant](https://blog.korolevalab.com/projects/medical-assistant/) |

`experiments/` draws the covers of the portfolio's experiments from each project's own pictures.

The articles are written in the same private workspace as the
[ML Samurai](https://github.com/mlsamurai) courses and published here. The figures are drawn by the small library in
`tools/figures/`, which needs the courses' helper package:
`pip install git+https://github.com/mlsamurai/transformers-from-scratch`. Run the scripts from the repository's
root, so that `tools` can be imported.

## License

Code under the [MIT License](LICENSE). The texts of the articles with a DOI are also published under CC BY 4.0 on
Zenodo.
