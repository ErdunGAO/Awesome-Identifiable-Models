# Awesome Identifiable Models
This repo is a collection of AWESOME things about identifiable models, mainly focusing on the recent developments on Nonlinear ICA and its extensions, and including papers, codes, etc. Feel free to fork.

![](https://img.shields.io/badge/Resources-@CLeaR_Unimelb-red.svg) ![](https://img.shields.io/badge/License-@MIT-green.svg)

# Theoretical results on ICA

## Linear ICA
- Independent Component Analysis. [[Book]](https://www.cs.helsinki.fi/u/ahyvarin/papers/bookfinal_ICA.pdf)
- Binary Independent Component Analysis via Non-stationarity. [[Paper]](https://arxiv.org/pdf/2111.15431.pdf)

## Nonlinear ICA
### Temporal Structures
- (TCL) Unsupervised Feature Extraction by Time-Contrastive Learning and Nonlinear ICA. [[NeurIPS16]](https://www.cs.helsinki.fi/u/ahyvarin/papers/NIPS16.pdf) [[Codes]](https://github.com/hmorioka/TCL)
- (PCL) Nonlinear ICA of Temporally Dependent Stationary Sources. [[AISTATS17]](https://www.cs.helsinki.fi/u/ahyvarin/papers/AISTATS17.pdf)

### Auxiliary Information
- (GCL) Nonlinear ICA Using Auxiliary Variables and Generalized Contrastive Learning. [[AISTATS19]](https://arxiv.org/pdf/1805.08651.pdf)
- (iVAE) Variational autoencoders and nonlinear ica: A unifying framework. [[AISTATS20]](https://arxiv.org/pdf/1907.04809.pdf) [[codes]](https://github.com/ilkhem/icebeem/tree/master/models/ivae)

### Multi-Views
- The Incomplete Rosetta Stone Problem: Identifiability Results for Multi-View Nonlinear ICA. [[UAI19]](https://arxiv.org/pdf/1905.06642.pdf)

### Theories
- On Finite-Sample Identifiability of Contrastive Learning-Based Nonlinear Independent Component Analysis. [[ICML22]](https://web.engr.oregonstate.edu/~fuxia/ICML2022_finite_sample.pdf)

## Independent mechanisms analysis (IMA)
- Independent mechanism analysis, a new concept? [[NeurIPS21]](https://proceedings.neurips.cc/paper/2021/file/edc27f139c3b4e4bb29d1cdbc45663f9-Paper.pdf) [[codes]](https://github.com/lgresele/independent-mechanism-analysis)
- Embrace the Gap: VAEs Perform Independent Mechanism Analysis. [[arxiv22]](https://arxiv.org/pdf/2206.02416.pdf) [[codes]](https://github.com/rpatrik96/ima-vae)

# Methods
- (GIN) Disentanglement by Nonlinear ICA with General Incompressible-flow Networks (GIN). [[ICLR20]](https://arxiv.org/pdf/2001.04872.pdf) [[codes]](https://github.com/VLL-HD/GIN)
- (ICE-BeeM) ICE-BeeM: Identifiable Conditional Energy-Based Deep Models Based on Nonlinear ICA. [[NeurIPS20]](https://proceedings.neurips.cc/paper/2020/file/962e56a8a0b0420d87272a682bfd1e53-Paper.pdf) [[codes]](https://github.com/ilkhem/icebeem)
- Robust contrastive learning and nonlinear ICA in the presence of outliers. [[UAI20]](http://proceedings.mlr.press/v124/sasaki20b/sasaki20b.pdf)
- Learning identifiable and interpretable latent models of high-dimensional neural activity using pi-VAE. [[NeurIPS20]](https://proceedings.neurips.cc/paper/2020/file/510f2318f324cf07fce24c3a4b89c771-Paper.pdf)
- Hidden Markov Nonlinear ICA: Unsupervised Learning from Nonstationary Time Series. [[UAI20]](http://proceedings.mlr.press/v124/halva20a/halva20a.pdf)
- Towards Nonlinear Disentanglement in Natural Data with Temporal Sparse Coding. [[ICLR21]](https://arxiv.org/pdf/2007.10930.pdf) [[codes]](https://github.com/bethgelab/slow_disentanglement)
- Multiple Environments Can Reduce Indeterminacy in VAEs. [[NeurIPS21]](https://why21.causalai.net/papers/WHY21_40.pdf)
- On Linear Identifiability of Learned Representations. [[ICML21]](http://proceedings.mlr.press/v139/roeder21a/roeder21a.pdf)
- When is Unsupervised Disentanglement Possible? [[NeurIPS21]](https://proceedings.neurips.cc/paper/2021/file/29586cb449c90e249f1f09a0a4ee245a-Paper.pdf)
- An Identifiable Double VAE For Disentangled Representations. [[ICML21]](http://proceedings.mlr.press/v139/mita21a/mita21a.pdf)
- Contrastive Learning Inverts the Data Generating Process. [[ICML21]](http://proceedings.mlr.press/v139/zimmermann21a/zimmermann21a.pdf) [[codes]](https://github.com/brendel-group/cl-ica)
- Disentangling Identifiable Features from Noisy Data with Structured Nonlinear ICA. [[NeurIPS21]](https://openreview.net/pdf?id=52XXcK8jY0J)
- Disentanglement via Mechanism Sparsity Regularization: A New Principle for Nonlinear ICA. [[CLeaR22]](https://openreview.net/pdf?id=dHsFFekd_-o)
- Independent mechanism analysis, a new concept? [[NeurIPS21]](https://proceedings.neurips.cc/paper/2021/file/edc27f139c3b4e4bb29d1cdbc45663f9-Paper.pdf)
- Properties from mechanisms: an equivariance perspective on identifiable representation learning. [[ICLR22]](https://arxiv.org/pdf/2110.15796.pdf)
- Nonlinear ICA Using Volume-Preserving Transformations. [[ICLR22]](https://openreview.net/pdf?id=AMpki9kp8Cn)
- I Don’t Need u: Identifiable Non-Linear ICA Without Side Information. [[Paper]](https://arxiv.org/pdf/2106.05238.pdf)
- On the Identifiability of Nonlinear ICA with Unconditional Priors. [[ICLR22workshop]](https://openreview.net/pdf?id=BW44SrOU9g5)
- Weakly Supervised Representation Learning with Sparse Perturbations. [[arxiv22]](https://arxiv.org/pdf/2206.01101.pdf)
- WICA: nonlinear weighted ICA. [[arxiv22]](https://arxiv.org/pdf/2001.04147.pdf) [[codes]](https://github.com/kondratevakate/fmri-component-analysis)
- On the Identifiability of Nonlinear ICA: Sparsity and Beyond. [[arxiv22]](https://arxiv.org/pdf/2206.07751.pdf)

# Applications
## Distribution Shift
- Self-Supervised Learning with Data Augmentations Provably Isolates Content from Style. [[NeurIPS21]](https://arxiv.org/pdf/2106.04619.pdf) [[codes]](https://github.com/ysharma1126/ssl_identifiability)
- On Linear Identifiability of Learned Representations. [[ICML21]](http://proceedings.mlr.press/v139/roeder21a/roeder21a.pdf)
- (IC-ERM) Towards efficient representation identification in supervised learning. [[CLeaR22]](https://openreview.net/pdf?id=7UwoSnMDXWE) [[codes]](https://github.com/divyat09/ood_identification)
- Few-shot Domain Adaptation by Causal Mechanism Transfer. [[ICML20]](https://arxiv.org/pdf/2002.03497.pdf) [[codes]](https://github.com/takeshi-teshima/few-shot-domain-adaptation-by-causal-mechanism-transfer)

## Others
- (LaCIM) Recovering Latent Causal Factor for Generalization to Distributional Shifts. [[NeurIPS21]](https://proceedings.neurips.cc/paper/2021/file/8c6744c9d42ec2cb9e8885b54ff744d0-Paper.pdf) [[codes]](https://github.com/wubotong/LaCIM)
- Supercharging Imbalanced Data Learning With Energy-based Contrastive Representation Transfer. [[NeurIPS21]](https://proceedings.neurips.cc/paper/2021/file/b151ce4935a3c2807e1dd9963eda16d8-Paper.pdf) [[codes]](https://github.com/ZidiXiu/ECRT)
- Invariant Causal Representation Learning for Out-of-Distribution Generalization. [[ICLR22]](https://openreview.net/pdf?id=-e4EXDWXnSn)
- A unified view for unsupervised representation learning with density ratio estimation: Maximization of mutual information, nonlinear ICA and nonlinear subspace estimation. [[Paper]](https://arxiv.org/pdf/2101.02083.pdf)
- Local Disentanglement in Variational Auto-Encoders Using Jacobian L1 Regularization. [[NeurIPS21]](https://proceedings.neurips.cc/paper/2021/file/bfd2308e9e75263970f8079115edebbd-Paper.pdf)
- (LEAP) Learning Temporally Causal Latent Processes from General Temporal Data. [[ICLR22]](https://arxiv.org/pdf/2110.05428.pdf) [[codes]](https://github.com/weirayao/leap)
- (LiLY) Learning Latent Causal Dynamics. [[arXiv22]](https://arxiv.org/pdf/2202.04828.pdf)
- Independent Innovation Analysis for Nonlinear Vector Autoregressive Process. [[AISTATS21]](http://proceedings.mlr.press/v130/morioka21a/morioka21a.pdf)
- Causal Hidden Markov Model for Time Series Disease Forecasting. [[CVPR21]](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_Causal_Hidden_Markov_Model_for_Time_Series_Disease_Forecasting_CVPR_2021_paper.pdf)
- Provable concept learning for interpretable predictions using variational inference. [[arXiv22]](https://arxiv.org/pdf/2204.00492.pdf) [[codes]](https://github.com/NikRuggeri/CLAP-interpretable-predictions)
- Partial Disentanglement for Domain Adaptation. [ICML22]

# More interesting papers
- Desiderata for Representation Learning: A Causal Perspective. [[Paper]](https://arxiv.org/pdf/2109.03795.pdf)

# Our Files
- A gentle introduction to Nonlinear ICA. [[Notes]](https://github.com/ErdunGAO/Research-Files/blob/main/Identifiable%20Generative%20Models.pdf)

# Other papers (Ignorable)
- VAEBM: A Symbiosis between Variational Autoencoders and Energy-based Models. [[ICLR21]](https://arxiv.org/pdf/2010.00654.pdf) [[codes]](https://github.com/NVlabs/VAEBM)
