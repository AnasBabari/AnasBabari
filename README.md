# Anas Babari

I build developer tools, web applications, and machine-learning projects with Python and TypeScript.

## Selected work

### [RepoDNA](https://github.com/AnasBabari/RepoDNA)

A tool for exploring an unfamiliar codebase through interactive architecture maps. It reads Python, JavaScript, and TypeScript source to identify files, symbols, imports, and routes without running the repository's code.

The project combines a browser interface with static-analysis engines and graph exports. Its documentation covers the decisions behind bounded parsing, local analysis, and reporting uncertain relationships. It does not use an LLM.

[Try RepoDNA](https://repodna-one.vercel.app) · [Engineering decisions](https://github.com/AnasBabari/RepoDNA/tree/main/docs/adr)

### [HanPath](https://github.com/AnasBabari/HanPath)

A Chinese-learning application with vocabulary lessons, spaced repetition, graded stories, and an AI tutor. Learning progress stays in the browser and can be exported and restored.

Built with React and TypeScript, with server-side handling for tutor requests. The engineering work includes progress validation, offline caching, accessibility checks, and request quotas.

[Try HanPath](https://han-path.vercel.app)

### [Signal Seven](https://github.com/AnasBabari/stock-predictor-lstm)

A stock-research application that separates seven-session price estimates from volatility forecasts. It combines a React interface with a Python/FastAPI backend, chronological model evaluation, and cached inference artifacts.

The research records include baseline comparisons, data provenance, limitations, and experiments that did not generalize. Historical model results are presented separately from the live application.

[Try Signal Seven](https://stock-predictor-lstm-two.vercel.app) · [Research record](https://github.com/AnasBabari/stock-predictor-lstm/blob/main/artifacts/PROVENANCE_FINAL.md)

## Technical interests

Developer tooling, applications that work reliably with local data, and evaluating machine-learning systems against useful baselines. I also work on [reinforcement learning for simulated racing](https://github.com/AnasBabari/torcs-ai).
