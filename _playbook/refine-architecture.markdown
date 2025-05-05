---
layout: best-practice
title: "Refine Architecture and Assess Latest Trend Impacts"
order: 150
icon: /assets/climate-icons/Icon-Settings.svg
number: "12"

section: Build Sustainable AI Products
chapter-tag: sustainable-ai

previous-page: optimize-model-training
next-page: use-your-influence

matter: |
  The way your AI system is architected — from how it’s tested to where it’s deployed — has a major and a long term impact on energy use and emissions. While these architecture-level decisions are often made by engineers and MLOps teams, we PMs can influence them by setting clear expectations and asking the right questions. This chapter equips you with the knowledge to do just that. A sustainability-first architecture not only cuts costs, it also helps avoid bloated systems, limits vendor lock-in, and keeps your AI products fast, lean, and scalable in the long run.

do: |
  - Start with a sound and optimized end-to-end architecture that lets you avoid technological and financial dependencies while providing consistent performance. This is true for traditional Computer vision and NLP pipelines or Agentic Workflows.

  - Testing, experimenting and benchmarking are energy-hungry due to their repetitive nature and should be done locally, especially in early stages. Great advances in compute power lets you run models on laptops or lightweight environments. Make sure they provide a realistic picture of what they will cost you once in production.

  - Scale up for training, but downscale for inference and don’t over-provision your production environments.  Production should be designed for scale but limited to very specific usage to limit performance issues (i.e Hallucination, Model drifting, etc.)

  - Optimize your GenAI prompts because not all prompts are created equal. Complex prompts (with detailed steps, examples, and restrictions) are not always better. Breaking them into simpler, sequential  steps or using prompt compression can often yield better, more consistent results and efficiency. Test and iterate to find what works best.

  - Nurture win-win situation for Product and Engineering/MLOps (Machine Learning Operations) with model optimization. Techniques like quantization, pruning, reduce model size, making deployments and maintenance more efficient, greener and cheaper—and they can run on lower-power devices, too.

  - Apply GreenOps to MLOPs by monitoring and adjusting cloud regions with lower carbon intensity for both re-training and inference.

  - Encourage research / use of most efficient Hardware (AI chips)

success: |
  - 🧑💰 Optimized system design and resource allocation for better performance and lower costs

  - 🧑💰 Enhanced user experience leading to improved conversion rates and overall satisfaction

consider: |
  Bake sustainability into your system design. Keep things as simple as possible, reduce redundant tests, and be transparent about your system’s performance and energy use. That transparency can also open the door to partnerships that share your sustainability goals — like cloud vendors, MLOps platforms, and hardware providers.
---

<div class="bigquote">
  <span class="highlight">“Start of everything is transparency.”
”We should really be asking enough questions so we can make informed decisions without just believing that it’s the best and greatest”.</span>
</div>

<p style="text-align:center;">Dr Sasha Luccioni ,AI researcher, Founding member of Climate Change, and Climate lead at Hugging Face</a></p>