<h1 class="page-title">Self-Corrected Image Generation<br>with Explainable Latent Rewards</h1>

<p class="page-authors"><a href="#">Yinyi Luo</a><sup>1,2</sup>, <a href="#">Hrishikesh Gokhale</a><sup>1</sup>, <a href="#">Marios Savvides</a><sup>1</sup>, <a href="https://jd92.wang/">Jindong Wang</a><sup>3</sup>, <a href="https://shengfenghe.github.io/">Shengfeng He</a><sup>2</sup><sup>†</sup><br>1Carnegie Mellon University, 2Singapore Management University, 3William & Mary</p>

![Teaser](img/teaser1.png)

<div align="center">
<h1>Abstract</h1>
</div>

Despite significant progress in text-to-image generation, aligning outputs with complex prompts remains challenging, particularly for fine-grained semantics and spatial relations. This difficulty stems from the feed-forward nature of generation, which requires anticipating alignment without fully understanding the output. In contrast, evaluating generated images is more tractable. Motivated by this asymmetry, we propose **xLARD**, a self-correcting framework that uses multimodal large language models to guide generation through E**x**plainable **LA**tent **R**ewar**D**s. xLARD introduces a lightweight corrector that refines latent representations based on structured feedback from model-generated references. A key component is a differentiable mapping from latent edits to interpretable reward signals, enabling continuous latent-level guidance from non-differentiable image-level evaluations. This mechanism allows the model to understand, assess, and correct itself during generation. Experiments across diverse generation and editing tasks show that xLARD improves semantic alignment and visual fidelity while maintaining generative priors, offering a data-efficient and generalizable solution to bridging the gap between comprehension and synthesis. 