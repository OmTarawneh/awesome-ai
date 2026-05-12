<div align="center">

# 🧠 Awesome AI Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of the most valuable resources for learning Artificial Intelligence — courses, books, papers, libraries, blogs, and tools.
>
> **Mostly free. Mostly open-source. 100% high signal.**

[![License: CC0](https://img.shields.io/badge/License-CC0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![Last Updated](https://img.shields.io/badge/updated-2026--05-success)]()

</div>

---

## About This List

This is not a roadmap. It's a **library** — a hand-picked shelf of the resources we think are genuinely worth your time across every major topic in AI. Pick what's relevant to you, ignore the rest. Most resources are completely free; a small number of paid items are included only where there's no free equivalent of similar quality.

The goal is signal, not completeness. Every resource here had to earn its place.

---

## 📚 Table of Contents

- [Mathematical Foundations](#mathematical-foundations-)
- [Python & Programming for ML](#python--programming-for-ml-)
- [Classical Machine Learning](#classical-machine-learning-)
- [Deep Learning](#deep-learning-)
- [Computer Vision (CNNs)](#computer-vision-cnns-)
- [NLP & Sequence Models](#nlp--sequence-models-)
- [Transformers & LLMs](#transformers--llms-)
- [LLM Engineering (RAG, Agents, Fine-tuning)](#llm-engineering-rag-agents-fine-tuning-)
- [Reinforcement Learning](#reinforcement-learning-)
- [Generative Models (GANs, Diffusion)](#generative-models-gans-diffusion-)
- [Graph Neural Networks](#graph-neural-networks-)
- [MLOps & Production ML](#mlops--production-ml-️)
- [ML Systems Design](#ml-systems-design-️)
- [📖 Must-Read Books](#-must-read-books)
- [📄 Foundational Papers](#-foundational-papers)
- [🎥 YouTube Channels](#-youtube-channels)
- [✍️ Blogs Worth Reading](#️-blogs-worth-reading)
- [📬 Newsletters & Podcasts](#-newsletters--podcasts)
- [🗂️ Datasets & Competitions](#️-datasets--competitions)
- [⚡ Free GPUs & Compute](#-free-gpus--compute)
- [💬 Communities](#-communities)
- [💸 Worth Paying For](#-worth-paying-for-honest-picks)
- [Contributing](#contributing)
- [License](#license)

---

## Mathematical Foundations 📐

> Vectors, gradients, distributions, matrices — the language AI is written in.

### Courses
- [MIT OCW 18.01 — Single Variable Calculus](https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/) — Free, full course with problem sets.
- [MIT OCW 18.02 — Multivariable Calculus](https://ocw.mit.edu/courses/18-02sc-multivariable-calculus-fall-2010/) — Vectors, gradients, Jacobians.
- [MIT OCW 18.06 — Linear Algebra (Gilbert Strang)](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) — The legendary linear algebra course.
- [MIT 18.S096 — Matrix Calculus for ML](https://www.youtube.com/playlist?list=PLUl4u3cNGP62EaLLH92E_VCN4izBKK6OE) — Closes the gap between calculus and deep learning.
- [Khan Academy — Probability & Statistics](https://www.khanacademy.org/math/statistics-probability) — Most accessible probability intro online.
- [Harvard Stat 110 — Probability](https://projects.iq.harvard.edu/stat110/home) — Joe Blitzstein's masterclass; harder, deeper.

### Visual & Intuitive
- [3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) — Watch this **before** doing the math. Geometric intuition that sticks.
- [3Blue1Brown — Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) — Same magic, for derivatives & integrals.
- [3Blue1Brown — Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) — Visual intro to backprop. Required.
- [Immersive Linear Algebra](http://immersivemath.com/ila/index.html) — Interactive online textbook.
- [Seeing Theory](https://seeing-theory.brown.edu/) — Visual introduction to probability & statistics. Beautiful.

### Book
- [Mathematics for Machine Learning](https://mml-book.com) — Free PDF. The single best math-for-ML book.

---

## Python & Programming for ML 🐍

> Half of being a good ML engineer is being a good Python engineer. These resources cover both ends.

- [Python for Everybody (PY4E)](https://www.py4e.com/) — Free, friendly intro for absolute beginners.
- [Real Python](https://realpython.com/) — Best intermediate Python tutorials on the web.
- [CS50P — Harvard's Intro to Python](https://cs50.harvard.edu/python/) — David Malan's signature production quality.
- [NumPy Illustrated](https://numpy.org/doc/stable/user/absolute_beginners.html) — The library at the heart of all of ML.
- [Pandas in 10 minutes](https://pandas.pydata.org/docs/user_guide/10min.html) — Official whirlwind tour.
- [Effective Python (Brett Slatkin)](https://effectivepython.com/) — Read once you're past beginner stage.

---

## Classical Machine Learning 📊

> Decision trees, gradient boosting, SVMs, k-means — the techniques that still drive most production ML systems.

### Courses
- [Stanford CS229 — Machine Learning (Andrew Ng)](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) — The gold standard. Long and worth it.
- [Coursera — Machine Learning Specialization (Andrew Ng)](https://www.coursera.org/specializations/machine-learning-introduction) — Lighter, more practical version of CS229. Auditable free.
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course) — Free, hands-on, ~15 hours.
- [Made With ML](https://madewithml.com/) — Modern end-to-end ML, project-driven.
- [Kaggle Learn — Intro & Intermediate ML](https://www.kaggle.com/learn) — Bite-sized, free, with notebooks.

### Books
- [An Introduction to Statistical Learning (ISLR)](https://www.statlearning.com/) — Free PDF. Read this first.
- [The Elements of Statistical Learning (ESL)](https://hastie.su.domains/ElemStatLearn/) — Free PDF. The deeper sequel.
- [Hands-On ML with Scikit-Learn, Keras & TensorFlow (Géron)](https://github.com/ageron/handson-ml3) — Code companion is free on GitHub.

### Libraries & Docs
- [scikit-learn](https://scikit-learn.org/stable/) — The classical ML toolkit. Their docs *are* a textbook.
- [XGBoost](https://xgboost.readthedocs.io/) — Still wins most Kaggle tabular comps.
- [LightGBM](https://lightgbm.readthedocs.io/) — Faster XGBoost.
- [CatBoost](https://catboost.ai/en/docs/) — Best for categorical-heavy data.

---

## Deep Learning 🧠

> Neural networks, backpropagation, training tricks, and the frameworks to put it all into practice.

### Courses
- [Neural Networks: Zero to Hero — Andrej Karpathy](https://karpathy.ai/zero-to-hero.html) — Build micrograd, makemore, then a GPT, all from scratch. Possibly the best free AI course ever made.
- [Practical Deep Learning for Coders — fast.ai](https://course.fast.ai/) — Top-down, hands-on. Train SOTA models in week one.
- [Stanford CS230 — Deep Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rOABXSygHTsbvUz4G_YQhOb) — Andrew Ng's deep learning course.
- [MIT 6.S191 — Introduction to Deep Learning](http://introtodeeplearning.com/) — Refreshed every year. Short and current.
- [NYU Deep Learning (Yann LeCun)](https://atcold.github.io/NYU-DLSP21/) — Includes self-supervised learning content years before it was mainstream.

### Book
- [Deep Learning — Goodfellow, Bengio, Courville](https://www.deeplearningbook.org/) — The "Bible." Free HTML version.
- [Dive into Deep Learning (D2L)](https://d2l.ai/) — Interactive book with PyTorch/TF/JAX code. Free.

### Frameworks
- [PyTorch](https://pytorch.org/docs/stable/) — The de-facto research and industry standard.
- [PyTorch 60-Minute Blitz](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html) — Fastest way to write your first net.
- [TensorFlow](https://www.tensorflow.org/) — Still widely used in production and on mobile/edge.
- [Keras 3](https://keras.io/) — High-level API. Now multi-backend (TF / PyTorch / JAX).
- [JAX](https://jax.readthedocs.io/) — Research-favorite for high-performance gradient computation.

---

## Computer Vision (CNNs) 🖼️

> Image classification, detection, segmentation, and the modern transformer-based vision models.

- [Stanford CS231n — CNNs for Visual Recognition](http://cs231n.stanford.edu/) — Karpathy's original course. Foundational.
- [Andrew Ng — CNN Lectures (DeepLearning.AI)](https://www.youtube.com/playlist?list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF) — Friendly, gentle version of CS231n.
- [PyTorch Vision Transfer Learning Tutorial](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html) — Fine-tune ResNet on your own data in under an hour.
- [Hugging Face Community Computer Vision Course](https://huggingface.co/learn/computer-vision-course) — Free, modern (includes ViTs).
- [Papers With Code — Computer Vision](https://paperswithcode.com/area/computer-vision) — SOTA models with code links.
- [timm (PyTorch Image Models)](https://github.com/huggingface/pytorch-image-models) — 1,000+ pre-trained vision models in one library.

---

## NLP & Sequence Models 🔁

> Word embeddings, RNNs, LSTMs — the pre-transformer NLP foundations still worth knowing.

- [Stanford CS224N — NLP with Deep Learning](https://web.stanford.edu/class/cs224n/) — Chris Manning's flagship NLP course.
- [Understanding LSTM Networks — Chris Olah](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) — The single best blog post on LSTMs.
- [The Illustrated Word2Vec — Jay Alammar](https://jalammar.github.io/illustrated-word2vec/) — Visual intro to embeddings.
- [PyTorch Sequence Models Tutorial](https://pytorch.org/tutorials/beginner/nlp/sequence_models_tutorial.html) — Hands-on RNN/LSTM in PyTorch.
- [spaCy 101](https://spacy.io/usage/spacy-101) — Industrial-strength NLP basics.

---

## Transformers & LLMs 🤖

> The architecture behind GPT, Claude, Gemini, LLaMA, and basically all of modern AI.

### Build Transformers from Scratch
- [Let's Build GPT from Scratch — Karpathy](https://www.youtube.com/watch?v=kCc8FmEb1nY) — 2 hours that will change your understanding forever.
- [Let's Build the GPT Tokenizer — Karpathy](https://www.youtube.com/watch?v=zduSFxRajkE) — Often-skipped, hugely valuable.
- [The Annotated Transformer (Harvard NLP)](http://nlp.seas.harvard.edu/2018/04/03/attention.html) — Paper + working PyTorch code, line by line.
- [Transformers from Scratch — Peter Bloem](https://peterbloem.nl/blog/transformers) — Best long-form blog explanation.

### Visual & Intuitive
- [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/) — Iconic. Read it.
- [The Illustrated GPT-2 — Jay Alammar](https://jalammar.github.io/illustrated-gpt2/) — Same author, GPT edition.

### Courses
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) — Free, hands-on, regularly updated. Probably the best practical intro.
- [Stanford CS25 — Transformers United](https://web.stanford.edu/class/cs25/) — Guest-speaker series with leading researchers.
- [Karpathy — Intro to LLMs (1-hour talk)](https://www.youtube.com/watch?v=zjkBMFhNj_g) — The "what is an LLM" video to share with non-technical people.
- [Karpathy — Deep Dive into LLMs like ChatGPT](https://www.youtube.com/watch?v=7xTGNNLPyMI) — A longer, deeper version. Required viewing.

### Foundational Papers
- [Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762) — The transformer paper.
- [BERT (Devlin et al., 2018)](https://arxiv.org/abs/1810.04805) — Bidirectional pre-training.
- [GPT-3 (Brown et al., 2020)](https://arxiv.org/abs/2005.14165) — Few-shot learning emerges from scale.
- [Chinchilla (Hoffmann et al., 2022)](https://arxiv.org/abs/2203.15556) — Compute-optimal training laws.
- [LLaMA (Touvron et al., 2023)](https://arxiv.org/abs/2302.13971) — The model that kicked off open-source LLMs.

---

## LLM Engineering (RAG, Agents, Fine-tuning) 🧩

> Building production applications on top of large language models.

### Foundations
- [Open-Source LLM Course — Maxime Labonne](https://github.com/mlabonne/llm-course) — Three tracks: fundamentals, scientist, engineer. The single best LLM resource on GitHub.
- [Full Stack LLM Bootcamp](https://fullstackdeeplearning.com/llm-bootcamp/) — Free recordings of the legendary 2023 bootcamp.
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) — Free, 1–2 hour focused courses on prompting, RAG, agents, evals. Co-taught with industry leaders.
- [Anthropic — Build with Claude Cookbook](https://github.com/anthropics/anthropic-cookbook) — Patterns for prompt engineering, tool use, and agents.
- [Anthropic Prompt Engineering Guide](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview) — Concise, current, vendor-agnostic principles.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Same idea, OpenAI flavor.

### Agents & Tool Use
- [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) — Free, certificate available. Covers smolagents, LlamaIndex, LangGraph.
- [Hugging Face MCP Course](https://huggingface.co/learn/mcp-course) — Model Context Protocol fundamentals.
- [LangChain Academy](https://academy.langchain.com/) — Free courses on LangChain & LangGraph.

### Frameworks
- [LangChain](https://python.langchain.com/) — The most popular LLM-app framework.
- [LlamaIndex](https://docs.llamaindex.ai/) — Excellent for RAG.
- [Haystack](https://docs.haystack.deepset.ai/) — Production-grade RAG/search.
- [DSPy](https://dspy.ai/) — Programmatic prompting, "compiles" prompts for you.
- [Instructor](https://python.useinstructor.com/) — Structured outputs from any LLM, dead simple.
- [smolagents](https://huggingface.co/docs/smolagents/) — Tiny, hackable agent framework.
- [Ollama](https://ollama.com/) — Run open-source LLMs locally with one command.
- [vLLM](https://docs.vllm.ai/) — High-throughput LLM serving.

### Fine-tuning
- [Unsloth](https://github.com/unslothai/unsloth) — Fine-tune LLMs 2× faster with 70% less memory. Free notebooks.
- [Axolotl](https://github.com/OpenAccess-AI-Collective/axolotl) — Production fine-tuning framework.
- [TRL (Hugging Face)](https://huggingface.co/docs/trl) — Reinforcement Learning + SFT for transformers.

---

## Reinforcement Learning 🎮

> Training agents through interaction with their environment — from Q-learning to PPO and beyond.

- [Stanford CS234 — Reinforcement Learning](https://www.youtube.com/playlist?list=PLoROMvodv4rN4wG6Nk6sNpTEbuOSosZdX) — Emma Brunskill's flagship course.
- [DeepMind x UCL RL Course (David Silver)](https://www.youtube.com/playlist?list=PLqYmG7hTraZBKeNJ-JE_eyJHZ7XgBoAyb) — Classic. Still relevant.
- [Hugging Face Deep RL Course](https://huggingface.co/learn/deep-rl-course) — Free, hands-on, train agents and share to the Hub.
- [OpenAI Spinning Up](https://spinningup.openai.com/) — Practical implementations of core RL algorithms.
- [Reinforcement Learning: An Introduction — Sutton & Barto](http://incompleteideas.net/book/the-book.html) — Free PDF. The RL book.
- [Gymnasium](https://gymnasium.farama.org/) — OpenAI Gym's actively maintained successor.
- [Stable-Baselines3](https://stable-baselines3.readthedocs.io/) — Reliable PyTorch implementations of RL algorithms.

---

## Generative Models (GANs, Diffusion) 🎨

> Image, audio, and video generation with GANs, VAEs, and diffusion models.

- [Hugging Face Diffusion Models Course](https://huggingface.co/learn/diffusion-course) — Free, project-based.
- [Lilian Weng — What are Diffusion Models?](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) — Best single article on diffusion theory.
- [The Annotated Diffusion Model](https://huggingface.co/blog/annotated-diffusion) — Paper + PyTorch code line by line.
- [PyTorch DCGAN Tutorial](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) — Train your first GAN.
- [diffusers (Hugging Face)](https://huggingface.co/docs/diffusers/) — The standard library for diffusion models.

---

## Graph Neural Networks 🌐

> Learning on graph-structured data — molecules, social networks, knowledge graphs.

- [Stanford CS224W — ML with Graphs](http://web.stanford.edu/class/cs224w/) — Jure Leskovec's flagship GNN course.
- [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/) — The main GNN library for PyTorch.
- [Deep Graph Library (DGL)](https://www.dgl.ai/) — Framework-agnostic alternative.
- [Distill — A Gentle Introduction to GNNs](https://distill.pub/2021/gnn-intro/) — Interactive and gorgeous.

---

## MLOps & Production ML ⚙️

> Taking models from notebook to production — pipelines, serving, monitoring, and versioning.

### Courses
- [DataTalks.Club — MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) — Free, project-based, run annually with community support.
- [Stanford CS329S — ML Systems Design](https://stanford-cs329s.github.io/) — Chip Huyen's course.
- [Made With ML — End-to-End MLOps](https://madewithml.com/) — Free, production-grade.
- [Evidently AI — ML Observability Course](https://www.evidentlyai.com/ml-monitoring) — Free, monitoring & evaluation focused.
- [Chip Huyen — MLOps Resources](https://huyenchip.com/mlops/) — Curated list with sharp opinions.

### Experiment Tracking
- [MLflow](https://mlflow.org/docs/latest/) — Open-source, runs anywhere.
- [Weights & Biases](https://docs.wandb.ai/) — Free for personal use, great UX.

### Data & Model Versioning
- [DVC](https://dvc.org/doc) — Git for data.
- [LakeFS](https://lakefs.io/) — Git-like operations over object storage.

### Pipeline Orchestration
- [Kubeflow](https://www.kubeflow.org/docs/) — End-to-end on Kubernetes.
- [Argo Workflows](https://argo-workflows.readthedocs.io/) — Kubernetes-native workflows.
- [ZenML](https://docs.zenml.io/) — Lighter, framework-agnostic orchestration.
- [Prefect](https://docs.prefect.io/) — Modern Python workflow orchestration.

### Model Serving
- [BentoML](https://docs.bentoml.com/) — Build & ship AI apps.
- [Seldon Core](https://docs.seldon.io/) — Kubernetes-native model serving.
- [Ray Serve](https://docs.ray.io/en/latest/serve/index.html) — Scalable serving on Ray.

### Monitoring
- [Evidently AI](https://github.com/evidentlyai/evidently) — Drift, quality, and performance monitoring.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) — Open-source LLM observability.

---

## ML Systems Design 🏗️

> How real ML systems are designed, scaled, and operated at companies that ship AI in production.

- [Designing Machine Learning Systems — Chip Huyen](https://huyenchip.com/2022/06/14/book.html) — Industry-defining book. Worth buying.
- [Eugene Yan's writing on ML systems](https://eugeneyan.com/writing/) — Some of the best industry-grounded blog posts on the internet.
- [The Twelve-Factor App](https://12factor.net/) — Not ML-specific, but every ML engineer should read it.

---

## 📖 Must-Read Books

| Book | Why | Free? |
|---|---|---|
| [Mathematics for Machine Learning](https://mml-book.com) | The math you actually need | ✅ |
| [An Introduction to Statistical Learning](https://www.statlearning.com/) | Best ML intro book | ✅ |
| [Deep Learning (Goodfellow et al.)](https://www.deeplearningbook.org/) | The foundational DL textbook | ✅ |
| [Dive into Deep Learning](https://d2l.ai/) | Interactive, code-first | ✅ |
| [Reinforcement Learning (Sutton & Barto)](http://incompleteideas.net/book/the-book.html) | The RL book | ✅ |
| [Hands-On ML (Géron)](https://github.com/ageron/handson-ml3) | Best practical ML book | ⚠️ Book paid / Code free |
| [Designing ML Systems (Chip Huyen)](https://huyenchip.com/2022/06/14/book.html) | ML in production | 💰 Paid (worth it) |
| [Build a LLM from Scratch (Sebastian Raschka)](https://github.com/rasbt/LLMs-from-scratch) | Builds a GPT step-by-step | ⚠️ Book paid / Code free |

---

## 📄 Foundational Papers

A short list — read these *carefully*, ideally with the [Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) style notebooks.

- [ImageNet Classification with Deep CNNs (AlexNet, 2012)](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
- [Sequence to Sequence Learning (Sutskever et al., 2014)](https://arxiv.org/abs/1409.3215)
- [Adam Optimizer (Kingma & Ba, 2014)](https://arxiv.org/abs/1412.6980)
- [Deep Residual Learning / ResNet (He et al., 2015)](https://arxiv.org/abs/1512.03385)
- [Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762)
- [BERT (Devlin et al., 2018)](https://arxiv.org/abs/1810.04805)
- [GPT-3 (Brown et al., 2020)](https://arxiv.org/abs/2005.14165)
- [Vision Transformer (Dosovitskiy et al., 2020)](https://arxiv.org/abs/2010.11929)
- [Denoising Diffusion Probabilistic Models (Ho et al., 2020)](https://arxiv.org/abs/2006.11239)
- [CLIP (Radford et al., 2021)](https://arxiv.org/abs/2103.00020)
- [Chinchilla / Scaling Laws (Hoffmann et al., 2022)](https://arxiv.org/abs/2203.15556)
- [LoRA (Hu et al., 2021)](https://arxiv.org/abs/2106.09685)

**Track new papers:**
- [arXiv-sanity](https://arxiv-sanity-lite.com/) — Karpathy's filter for the arXiv firehose.
- [Papers With Code](https://paperswithcode.com/) — Papers + their open-source implementations.
- [Hugging Face Daily Papers](https://huggingface.co/papers) — Community-curated, daily.

---

## 🎥 YouTube Channels

- [Andrej Karpathy](https://www.youtube.com/@AndrejKarpathy) — Zero to Hero, LLM deep dives. Unmatched.
- [3Blue1Brown](https://www.youtube.com/@3blue1brown) — Visual math + neural nets.
- [Yannic Kilcher](https://www.youtube.com/@YannicKilcher) — Best paper walkthroughs on YouTube.
- [Two Minute Papers](https://www.youtube.com/@TwoMinutePapers) — Fast research summaries.
- [StatQuest with Josh Starmer](https://www.youtube.com/@statquest) — Beginner-friendly stats & ML.
- [Sentdex](https://www.youtube.com/@sentdex) — Hands-on Python ML tutorials.
- [DeepLearningAI](https://www.youtube.com/@Deeplearningai) — Andrew Ng's official channel.
- [Hugging Face](https://www.youtube.com/@HuggingFace) — Tutorials & releases.
- [Umar Jamil](https://www.youtube.com/@umarjamilai) — Build transformers, LLaMA, RLHF from scratch.

---

## ✍️ Blogs Worth Reading

- [Lilian Weng](https://lilianweng.github.io/) — Deep, technical surveys (diffusion, RLHF, agents).
- [Sebastian Raschka — Ahead of AI](https://magazine.sebastianraschka.com/) — LLM internals, fine-tuning, evals.
- [Chip Huyen](https://huyenchip.com/blog/) — ML systems, MLOps, careers.
- [Jay Alammar](https://jalammar.github.io/) — Illustrated guides to transformers/BERT/etc.
- [Eugene Yan](https://eugeneyan.com/writing/) — Applied ML at Amazon scale.
- [Andrej Karpathy — Blog](https://karpathy.github.io/) — Short, dense, gold.
- [Simon Willison](https://simonwillison.net/) — Best daily LLM news + experiments.
- [Distill.pub](https://distill.pub/) — Interactive, visual ML research papers.
- [Hugging Face Blog](https://huggingface.co/blog) — Tutorials, releases, model cards.

---

## 📬 Newsletters & Podcasts

### Newsletters
- [The Batch — Andrew Ng / DeepLearning.AI](https://www.deeplearning.ai/the-batch/) — Weekly, balanced, must-read.
- [Import AI — Jack Clark](https://importai.substack.com/) — Sharp, opinionated, weekly.
- [Ben's Bites](https://bensbites.com/) — Daily AI news, short.
- [Latent Space](https://www.latent.space/) — Deep dives on the AI engineering stack.
- [TLDR AI](https://tldr.tech/ai) — 5-minute daily roundup.

### Podcasts
- [Lex Fridman](https://lexfridman.com/podcast/) — Long-form interviews with researchers.
- [Latent Space Podcast](https://www.latent.space/podcast) — Best podcast for AI engineers.
- [The Gradient Podcast](https://thegradientpub.substack.com/s/podcast) — Researcher interviews.
- [Practical AI](https://changelog.com/practicalai) — Friendly, practitioner-focused.
- [Dwarkesh Patel](https://www.dwarkesh.com/) — Deep technical interviews with frontier-lab researchers.

---

## 🗂️ Datasets & Competitions

- [Hugging Face Datasets](https://huggingface.co/datasets) — Tens of thousands of datasets, one-line load.
- [Kaggle Datasets](https://www.kaggle.com/datasets) — Plus competitions to test your skills.
- [Papers With Code Datasets](https://paperswithcode.com/datasets) — Benchmarks indexed by task.
- [Google Dataset Search](https://datasetsearch.research.google.com/) — Find any public dataset.
- [Common Crawl](https://commoncrawl.org/) — The web, free.
- [OpenML](https://www.openml.org/) — Curated ML datasets and benchmarks.

---

## ⚡ Free GPUs & Compute

- [Google Colab](https://colab.research.google.com/) — Free T4 GPU. The classic.
- [Kaggle Notebooks](https://www.kaggle.com/code) — Free P100 / T4 x2, 30 hr/week.
- [Lightning AI Studios](https://lightning.ai/) — Generous free tier with persistent envs.
- [Hugging Face Spaces](https://huggingface.co/spaces) — Free CPU + paid GPU upgrades, great for demos.
- [Modal](https://modal.com/) — Serverless GPUs; $30/mo credit on free tier.
- [Paperspace Gradient](https://www.paperspace.com/gradient) — Free GPU notebooks.

---

## 💬 Communities

- [Hugging Face Discord](https://huggingface.co/join/discord) — Largest open AI community.
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) — Research-heavy.
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) — Best place for open-source LLM news.
- [EleutherAI Discord](https://www.eleuther.ai/) — Open-source LLM research community.
- [LatentSpace Discord](https://discord.gg/xJJMRaWCRt) — AI engineering practitioners.
- [Fast.ai Forums](https://forums.fast.ai/) — Friendly, beginner-supportive.
- [Kaggle Forums](https://www.kaggle.com/discussions) — Competition-driven, very practical.

---

## 💸 Worth Paying For (Honest Picks)

> Most of this roadmap is free. These few paid resources are exceptional value if you have the budget.

- **[Designing Machine Learning Systems — Chip Huyen](https://huyenchip.com/2022/06/14/book.html)** (~$40) — No free equivalent for production ML thinking.
- **[Hands-On ML with Scikit-Learn, Keras & TensorFlow (Géron)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)** (~$50) — Best practical ML book in print.
- **[Build a Large Language Model from Scratch — Sebastian Raschka](https://www.manning.com/books/build-a-large-language-model-from-scratch)** (~$50) — Walks you through coding GPT step-by-step. Code is free on GitHub.
- **[Coursera ML / DL Specializations](https://www.coursera.org/specializations/machine-learning-introduction)** (~$50/mo) — Pay for the certificate; audit is free.
- **[Weights & Biases Pro](https://wandb.ai/site/pricing)** — Free tier is excellent for individuals; pay only when you scale.

---

## Contributing

PRs welcome! Please follow these rules:

1. **Quality bar:** the resource must be something you'd recommend to a friend, not just "comprehensive."
2. **Free preferred:** paid resources go in the "Worth Paying For" section, with clear value justification.
3. **Working links only:** broken links will be removed.
4. **No course drops:** every new entry needs a one-line "why this is here" description.

To suggest a resource, open an issue or send a PR editing this `README.md`.

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work. Resources linked herein remain under their respective licenses.

---

<div align="center">

**⭐ If this helped you, star the repo — it's the only way these lists stay alive.**

</div>
