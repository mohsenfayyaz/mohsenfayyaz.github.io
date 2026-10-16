---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About me
======
Hi! I am a computer science Ph.D. student at <b>[UCLA](https://www.ucla.edu/)</b> in the [PLUS Lab](https://plus-lab.github.io/){:target="_blank"}, advised by [Prof. Nanyun (Violet) Peng](https://violetpeng.github.io/){:target="_blank"}. Previously, I received my master's degree at the <b>University of Tehran</b> advised by [Prof. Yadollah Yaghoobzadeh](https://yyaghoobzadeh.github.io/){:target="_blank"} and [Prof. Mohammad Taher Pilehvar](https://pilehvar.github.io/){:target="_blank"}. In summer 2025, I was a research intern at <b>Adobe Research</b>.
<!-- Hi! I am a master's student at the <b>University of Tehran</b>, and I have the pleasure of working with [Mohammad Taher Pilehvar](https://pilehvar.github.io/){:target="_blank"}, [Yadollah Yaghoobzadeh](https://yyaghoobzadeh.github.io/){:target="_blank"}, and [Azadeh Shakery](https://ece.ut.ac.ir/en/~shakery){:target="_blank"} on natural language processing (NLP) and deep learning. -->

My research focuses on <b>Interpretability for Robust and Controllable LLM Systems</b>. Recently, I have been working on:
- <b>Steering Mixture-of-Experts LLMs</b>: detecting behavior-linked experts and (de)activating them at inference time to control safety and faithfulness without any fine-tuning ([SteerMoE, ICLR 2026](https://arxiv.org/abs/2509.09660){:target="_blank"}), and understanding how MoE routing works across languages ([ICLR 2026](https://arxiv.org/abs/2510.04694){:target="_blank"}).
- <b>Retrieval and RAG</b>: exposing the short, early, and literal biases that make dense retrievers outrank factual evidence ([ACL 2025](https://arxiv.org/abs/2503.05037){:target="_blank"}), and vision-centric evaluation of retrieval-augmented multimodal models ([MRAG-Bench, ICLR 2025](https://arxiv.org/abs/2410.08182){:target="_blank"}).
- <b>Interpretability</b>: token attribution in Transformers ([ACL 2023](https://aclanthology.org/2023.acl-long.149/){:target="_blank"}, [NAACL 2022](https://aclanthology.org/2022.naacl-main.19){:target="_blank"}), and probing the knowledge encoded in pre-trained language models ([ACL 2022](https://aclanthology.org/2022.acl-long.144/){:target="_blank"}, [BlackboxNLP@EMNLP 2021](https://aclanthology.org/2021.blackboxnlp-1.29){:target="_blank"}).

Feel free to [email](mailto:mohsenfayyaz@cs.ucla.edu) me or check my [Curriculum Vitae](/files/MohsenFayyaz_CV.pdf){:target="_blank"}.

Featured Research
======
------
<div style="border: 1px solid #ddd; border-left: 4px solid #2f7fc1; border-radius: 6px; padding: 14px 18px; margin-bottom: 1.5em; font-size: 15.5px;">
	<b><a href="https://arxiv.org/abs/2509.09660" target="_blank">Steering MoE LLMs via Expert (De)Activation</a></b> &nbsp;<span class="venue-badge">ICLR 2026</span><br>
	<b><u>Mohsen Fayyaz</u></b>, Ali Modarressi, Hanieh Deilamsalehy, Franck Dernoncourt, Ryan Rossi, Trung Bui, Hinrich Schütze, Nanyun Peng<br>
	<p style="margin: 0.6em 0;">
		<b>SteerMoE</b> steers Mixture-of-Experts LLMs by detecting experts whose activation differs between paired inputs with opposite behaviors, then turning them on or off at inference time, with no retraining or weight updates.
		Across 11 benchmarks and 6 LLMs, steering improves <b>safety by up to +20%</b> and <b>faithfulness by up to +27%</b>.
		In adversarial mode, deactivating safety-linked experts sharply reduces safety, and combined with existing jailbreaks it <b>bypasses all safety guardrails</b>, exposing a new dimension of <i>alignment faking</i> hidden within experts.
	</p>
	<a href="https://arxiv.org/abs/2509.09660" target="_blank">[📝 paper]</a>
	<a href="https://github.com/adobe-research/SteerMoE" target="_blank">[💻 code]</a>
</div>

News
======
------
<div class="news-list">
<ul>
	<li>
		<b>Jan 2026</b>: Two papers accepted to <span class="venue-badge">ICLR 2026</span>! 🎉
		<ul>
			<li>"Steering MoE LLMs via Expert (De)Activation" (SteerMoE) <a href="https://arxiv.org/abs/2509.09660" target="_blank">[paper]</a> <a href="https://github.com/adobe-research/SteerMoE" target="_blank">[code]</a></li>
			<li>"Multilingual Routing in Mixture-of-Experts" <a href="https://arxiv.org/abs/2510.04694" target="_blank">[paper]</a></li>
		</ul>
	</li>
	<li>
		<b>Sep 2025</b>: Released <b>SteerMoE</b>, our work from my Adobe Research internship on steering MoE LLMs by (de)activating experts at inference time.
		<a href="https://arxiv.org/abs/2509.09660" target="_blank">[paper]</a>
		<a href="https://github.com/adobe-research/SteerMoE" target="_blank">[code]</a>
	</li>
	<li>
		<b>Jun 2025</b>: Started a research internship at <b>Adobe Research</b> in Seattle.
	</li>
	<li>
		<b>May 2025</b>: Our paper "Collapse of Dense Retrievers: Short, Early, and Literal Biases Outranking Factual Evidence" has been accepted to <span class="venue-badge acl">ACL 2025</span> main conference!
		<a href="https://arxiv.org/abs/2503.05037" target="_blank">[paper]</a>
		<a href="https://huggingface.co/datasets/mohsenfayyaz/ColDeR" target="_blank">[dataset]</a>
	</li>
	<li>
		<b>Jan 2025</b>: "MRAG-Bench: Vision-Centric Evaluation for Retrieval-Augmented Multimodal Models" has been accepted to <span class="venue-badge">ICLR 2025</span>!
		<a href="https://arxiv.org/abs/2410.08182" target="_blank">[paper]</a>
	</li>
</ul>
<details>
<summary>Show older news</summary>
<ul>
	<li>
		<b>Jul 2024</b>: New preprint <span class="venue-badge arxiv">arXiv</span> "Evaluating Human Alignment and Model Faithfulness of LLM Rationale".
		<a href="https://arxiv.org/abs/2407.00219" target="_blank">[paper]</a>
	</li>
	<li>
		<b>Sep 2023</b>: Started my Ph.D. in Computer Science at <b>UCLA</b>, advised by Prof. Nanyun (Violet) Peng.
	</li>
	<li>
		<b>Jul 2023</b>: Our paper "DecompX: Explaining Transformers Decisions by Propagating Token Decomposition" has been accepted to <span class="venue-badge acl">ACL 2023</span>!
		<a href="https://aclanthology.org/2023.acl-long.149/" target="_blank">[paper]</a>
	</li>
	<li>
		<b>Nov 2022</b>: Our paper "BERT on a Data Diet: Finding Important Examples by Gradient-Based Pruning" has been accepted to <span class="venue-badge neurips">ENLSP @ NeurIPS 2022</span>!
		<a href="https://arxiv.org/abs/2211.05610" target="_blank">[paper]</a>
	</li>
	<li>
		<b>Apr 2022</b>: Our paper "GlobEnc: Quantifying Global Token Attribution by Incorporating the Whole Encoder Layer in Transformers" has been accepted to <span class="venue-badge acl">NAACL 2022</span> main conference!
		<a href="https://aclanthology.org/2022.naacl-main.19.pdf" target="_blank">[paper]</a>
		<a href="https://youtu.be/jgd9kUJlug4" target="_blank">[video]</a>
	</li>
	<li>
		<b>Mar 2022</b>: Our paper "Metaphors in Pre-Trained Language Models: Probing and Generalization Across Datasets and Languages" has been accepted to <span class="venue-badge acl">ACL 2022</span> main conference!
		<a href="https://aclanthology.org/2022.acl-long.144/" target="_blank">[paper]</a>
		<a href="https://www.youtube.com/watch?v=UKWFZSiP7OY" target="_blank">[video]</a>
	</li>
	<li>
		<b>Sep 2021</b>: Our paper "Not All Models Localize Linguistic Knowledge in the Same Place: A Layer-wise Probing on BERToids’ Representations" has been accepted to <span class="venue-badge acl">BlackboxNLP @ EMNLP 2021</span>!
		<a href="https://aclanthology.org/2021.blackboxnlp-1.29/">[paper]</a>
		<!-- <a href="/posts/layer-wise-probing-on-bertoids">[blog]</a> -->
	</li>
</ul>
</details>
</div>
