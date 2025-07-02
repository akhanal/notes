# 🌄 From CBIR to Agents: A Journey Reignited

_In 2005, I worked on content-based image retrieval (CBIR) in Nepal with my friends Basu and Bibek.  
Today, I’m relearning machine learning and building agents—reconnecting with a path I left behind years ago._

---

## 📸 2005 — The First Spark, Despite Doubts

Back then, we believed machines could understand images.

I was working on CBIR with my friends **Basu** and **Bibek**—three of us trying to make computers "see" using:
- **SIFT** descriptors,
- **Bag-of-Visual-Words**,
- **Inverted indexes**.

We were doing this from Nepal in 2005, driven by curiosity and belief.  
But the environment wasn’t always supportive.  
Some professors, focused on “proven” paths like digit recognition or check processing, discouraged us—saying those projects were “better” and more practical. They saw CBIR as too ambitious, too uncertain.

That skepticism was tough to face. But even then, we felt we were onto something bigger.

At the time, **neural networks** were used only for niche tasks—digit recognition, check processing, facial detection—but **not** for open-world problems like CBIR.

The neural networks of that era were relatively shallow and limited by:
- **Small datasets** (like MNIST or CIFAR),
- **Limited computational power** (CPUs rather than GPUs),
- **Simpler architectures**,
- And no large-scale, well-annotated datasets to train on.

Because of these constraints, they were unable to learn the complex, hierarchical features needed for general image understanding.

---

## 🕰️ Timeline: When Industry Adopted CBIR at Scale

While academic research in CBIR evolved steadily, major breakthroughs in real-world visual search started to appear after deep learning matured:

- **2001–2009** — Google Image Search initially relied on metadata and filenames, not content-based features.
- **2011** — **Google introduced "Search by Image"**, enabling reverse image search. It used hand-engineered features (e.g. SIFT), not deep learning.
- **2015** — **Pinterest launched “Visual Search”**, using deep learning to let users find similar objects in images.
- **2016** — **Google Photos added deep learning-based visual recognition**, enabling object, face, and scene search by content.
- **2017** — **Bing Visual Search** allowed region-based queries using deep learning for e-commerce and object matching.
- **2019** — **Amazon StyleSnap** introduced fashion recommendations from images using visual similarity models.
- **2020–2022** — Social and commerce platforms like **Snapchat**, **TikTok**, and **Instagram** used visual understanding for content discovery, moderation, and personalization.

These advances turned CBIR from academic theory into a mainstream technology—enabled by the breakthroughs that began with AlexNet.

---

## 🚀 Why ImageNet and AlexNet Changed Everything

The breakthrough came with **ImageNet**, created by **Fei-Fei Li**, who built a massive, richly labeled dataset of over 1.2 million images across 1,000 categories. This dataset was a game-changer: it provided the volume and diversity required for deep learning to thrive.

Building on this, **Alex Krizhevsky**, together with **Ilya Sutskever** and **Geoffrey Hinton**, designed and trained **AlexNet** in 2012. Ilya Sutskever’s expertise in scaling deep learning architectures and optimization was crucial in making training on such a large dataset feasible.

AlexNet introduced key innovations:
- Deeper and wider convolutional layers,
- **ReLU** activations for faster and better training,
- **Dropout** to prevent overfitting,
- And leveraging **GPU acceleration** to manage the massive computation.

This combination allowed the network to learn powerful, transferable visual features, marking a paradigm shift in computer vision.

Although AlexNet was trained for image classification, it was a **quantum leap for content-based image retrieval (CBIR)** as well. For the first time, a model could learn **generic, high-level visual representations** that captured semantics—rather than relying on handcrafted features like SIFT or HOG.

These learned features could be reused across tasks:
- for retrieval (finding similar images),
- for localization (object detection),
- and later, for captioning, segmentation, and even language grounding.

What began as a classification breakthrough laid the groundwork for **universal visual encoders**—a foundation upon which modern CBIR, vision-language models, and autonomous agents are now built.

---

## 🔥 2012 — The World Changed with AlexNet

AlexNet’s success was stunning:
- It outperformed traditional computer vision techniques by a large margin on ImageNet classification.
- It showed neural networks could learn from raw pixels without handcrafted features.
- It paved the way for deeper and more complex models.

This wasn’t just about classification.  
It was about **unlocking transferable, scalable learning**—something we had always hoped for.

---

## 🧠 Vision Inspired Language

What worked in vision soon crossed into NLP:
- **word2vec**, **GloVe** brought embedding-based representations,
- **Transformers** replaced RNNs with scalable attention,
- **BERT** and **GPT** showed that language could be learned end-to-end.

Just like ImageNet enabled CNNs, these models trained on massive corpora and became **general-purpose semantic engines**.

The same core idea:  
> Learn to represent the world through data—not rules.

---

## 🎯 2021 — Multimodal Models Bridge the Gap

Then came **CLIP** (Contrastive Language–Image Pretraining):
- Trained on 400M image–text pairs,
- Aligned visual and language representations in a shared space,
- Enabled zero-shot retrieval and semantic understanding across modalities.

This was CBIR—but reimagined with meaning, not just pixels.

---

## 🤖 Now — Agents Don’t Just Retrieve, They Act

Today, we’re entering the era of **autonomous agents**.

These systems:  
- Perceive (images, text, voice),  
- Plan (multi-step reasoning),  
- Use tools (APIs, code, memory),  
- Adapt (based on feedback),  
- And execute goals across tasks.

### 🏞️ Example: A Tourism Agent

> “Promote trekking in Annapurna this fall.”

An AI agent today can:  
1. **Retrieve and generate mountain visuals** (via CBIR or DALL·E),  
2. **Write captions and translations**,  
3. **Generate a promo video** with voiceover,  
4. **Post across platforms** using APIs,  
5. **Monitor engagement**, analyze what works,  
6. **Refine strategy** and adapt automatically.

This is no longer about retrieval—it's **decision-making, creation, and autonomous improvement**.

---

## 🌄 My Story: Relearning, Rebuilding, Reconnecting

I didn’t continue after 2005.  
I watched the field evolve—from SIFT to CNNs, from BoW to GPT, from vision to agents.

Along the way, I dabbled in software engineering and building large distributed systems.  
I learned about:  
- **Designing scalable, fault-tolerant architectures**,  
- **Distributed databases and caching**,  
- **Microservices and container orchestration**,  
- **Cloud infrastructure and deployment pipelines**,  
- **Monitoring, logging, and observability**.

These skills weren’t just useful for building software; they’re essential for building **real-world, scalable machine learning systems**—from data pipelines to model deployment and monitoring.

Now, I’m relearning what I left behind:  
- Rebuilding my knowledge in ML and DL,  
- Understanding how large language models and multimodal systems work,  
- Experimenting with tools to build autonomous agents.

I’m not here to catch up or claim I’m first.  
I’m here because I still believe in the **original dream**—and I want to be part of where it’s going next.

---

## 🙏 If You’re Reading This

Whether you're just starting out or returning like me:  

- You don’t need to be first.  
- You don’t need to invent the path.  
- You can rejoin later and continue the journey.  
- What you learned along other paths will come back to be helpful as well.  

What you build today—however small—might become the foundation for something huge.

Thanks for reading.

— **Ankit Khanal**
