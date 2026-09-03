# E-Commerce Bench website

Project website for [E-Commerce Bench](https://ecbench.github.io/), the 365-day long-horizon e-commerce benchmark for LLM agents.

- Paper: [arXiv:2608.30730](https://arxiv.org/abs/2608.30730)
- Code and data: [QwenLM/E-CommerceBench](https://github.com/QwenLM/E-CommerceBench)

## Local preview

Serve the repository over HTTP so the page can load `showcase_data.json`:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>. The site is static and deploys directly from the repository root with GitHub Pages.
