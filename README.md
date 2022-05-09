# Awesome Biologically Plausible Neural Networks

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A curated list of amazingly awesome biologically plausible neural networks papers, resources and shiny things.

Based on some of the internal journal clubs we had at the [CNS Group of Walter Senn and TMA Group of Mihai Petrovici](https://github.com/unibe-cns) 
* [BPBP JC](https://pad.riseup.net/p/F_ZO_lHFznVfFfiEpY7l-keep)
* [BP-RNN JC](https://pad.riseup.net/p/YAK7mHrzrjSNCI3LVE_G-keep)

Also have a look at [Awesome biologically motivated learning](https://github.com/jsalbert/awesome-biologically-motivated-learning) which includes some papers with biological motivation.

## Challenges for backprop to be biologically plausible
- Local plasticity rules
- Weight asymmetry
- Plausible connectivity
- Biological patterns of activity (for different phases of computation)
- Signed errors and unsigned neural activities
- Compatible with biological neuron models (dendrites and spikes)
- Prevention of catastrophic forgetting (this goes somewhat beyond 'biologically plausible', but it may be a perk of the models discussed)
- Time-continuous formulation possible
- Avoidance or explanation of derivatives: How does the synapse know to change its strength using the derivative of the neuron's activation?

### General
* 2003 | Xie, X., & Seung H.S. (2003). Equivalence of Backpropagation and Contrastive Hebbian Learning in a Layered Network. Neural Computation 15, 441–454.
* 2010 | Bernd Illing, Jean Ventura, Guillaume Bellec, Wulfram Gerstner, Local plasticity rules can learn deep representations using self-supervised contrastive predictions
[`arxiv`](https://arxiv.org/abs/2010.08262)
* 2015 | Lee, D. H., Zhang, S., Fischer, A., & Bengio, Y. (2015). Difference target propagation. In Joint european conference on machine learning and knowledge discovery in databases (pp. 498-515). Springer, Cham.
* 2017 | Scellier, B., & Bengio, Y. (2017). Equilibrium propagation: Bridging the gap between energy-based models and backpropagation. Frontiers in computational neuroscience, 11, 24.
* 2017 | Frerix, T., Möllenhoff, T., Moeller, M., & Cremers, D. (2017). Proximal backpropagation. arXiv preprint arXiv:1706.04638.
* 2017 | Guerguiev, J., Lillicrap, T. P., & Richards, B. A. (2017). Towards deep learning with segregated dendrites. ELife, 6, e22901.
* 2018 | Sacramento, J., Costa, R. P., Bengio, Y., & Senn, W. (2018). Dendritic cortical microcircuits approximate the backpropagation algorithm. arXiv preprint arXiv:1810.11393.
* 2019 | Mesnard, T., Vignoud, G., Sacramento, J., Senn, W., & Bengio, Y. (2019). Ghost units yield biologically plausible backprop in deep neural networks. arXiv preprint arXiv:1911.08585.
* 2020 | Millidge, B., Tschantz, A., Buckley, C. L., & Seth, A. (2020). Activation Relaxation: A Local Dynamical Approximation to Backpropagation in the Brain. arXiv preprint arXiv:2009.05359.
* 2020 | Meulemans, A., Carzaniga, F. S., Suykens, J. A., Sacramento, J., & Grewe, B. F. (2020). A theoretical framework for target propagation. arXiv preprint arXiv:2006.14331.
* 2021 | Payeur, A., Guerguiev, J., Zenke, F., Richards, B. A., & Naud, R. (2021). Burst-dependent synaptic plasticity can coordinate learning in hierarchical circuits. Nature Neuroscience, 1-10.
* 2021 | Clark, D. G., Abbott, L. F., & Chung, S. (2021). Credit Assignment Through Broadcasting a Global Error Vector. arXiv preprint arXiv:2106.04089. [`arxiv`](https://arxiv.org/pdf/2106.04089.pdf)

### Predictive Coding
* 2017 | Whittington, J. C., & Bogacz, R. (2017). An approximation of the error backpropagation algorithm in a predictive coding network with local hebbian synaptic plasticity. Neural computation, 29(5), 1229-1262.
* 2020 | Song, Y., Lukasiewicz, T., Xu, Z., & Bogacz, R. (2020). Can the brain do backpropagation?—exact implementation of backpropagation in predictive coding networks. Advances in neural information processing systems, 33, 22566.


### Energy-based Models
*Energy-based Models.*

* 2014 | Learning by the Dendritic Prediction of Somatic Spiking [`pdf`](https://linkinghub.elsevier.com/retrieve/pii/S0896627313011276)
* 2016 | Equilibrium Propagation: Bridging the Gap Between Energy-Based Models and Backpropagation [`arxiv`](http://arxiv.org/abs/1602.05179)
* 2016 | Random synaptic feedback weights support error backpropagation for deep learning [`pdf`](http://www.nature.com/articles/ncomms13276)
* 2017 | An Approximation of the Error Backpropagation Algorithm in a Predictive Coding Network with Local Hebbian Synaptic Plasticity [`pdf`](http://www.mitpressjournals.org/doi/10.1162/NECO_a_00949)
* 2018 | Dendritic cortical microcircuits approximate the backpropagation algorithm [`arxiv`](https://arxiv.org/abs/1810.11393)
* 2019 | Theories of Error Back - Propagation in the Brain [`pdf`](https://linkinghub.elsevier.com/retrieve/pii/S1364661319300129)


### Bioplausible learning in recurrent neur(on)al networks

* 1989 | RTRL (Real-Time Recurrent Learning) Original paper: R. J. Williams and D. Zipser, “A learning algorithm for continually running fully recurrent neural networks,” Neural computation, vol. 1, no. 2, pp. 270–280, 1989
* 2021 | Application to SNN: Zenke, F., and Neftci, E.O. (2021). Brain-Inspired Learning on Neuromorphic Substrates. Proceedings of the IEEE, 1–16, https://doi.org/10.1109/JPROC. 2020.3045625.
* 2020 | A solution to the learning dilemma for recurrent networks of spiking neurons https://www.nature.com/articles/s41467-020-17236-y
* 2020 | Kheradpisheh, S. R., & Masquelier, T. (2020). Temporal backpropagation for spiking neural networks with one spike per neuron. International Journal of Neural Systems, 30(06), 2050027.
* 2021 | Gauthier, D. J., Bollt, E., Griffith, A., & Barbosa, W. A. (2021). Next Generation Reservoir Computing. arXiv preprint arXiv:2106.07688.
* 2019 | Scellier, B., & Bengio, Y. (2019). Equivalence of equilibrium propagation and recurrent backpropagation. Neural computation, 31(2), 312-329.
* 2019 | Lillicrap, T. P., & Santoro, A. (2019). Backpropagation through time and the brain. Current opinion in neurobiology, 55, 82-89.
* 2021 | Colin Bredenberg, Benjamin Lyo, Eero Simoncelli, Cristina Savin: Impression learning: Online representation learning with synaptic plasticity
https://proceedings.neurips.cc/paper/2021/hash/615299acbbac3e21302bbc435091ad9f-Abstract.html

## Contributing and Collaborating
Please see [CONTRIBUTING](https://github.com/benelot/awesome-biologically-plausible-neural-networks/blob/master/CONTRIBUTING.md), [CODE-OF-CONDUCT](https://github.com/benelot/awesome-biologically-plausible-neural-networks/blob/master/CODE-OF-CONDUCT.md) and [COLLABORATING](https://github.com/benelot/awesome-biologically-plausible-neural-networks/blob/master/COLLABORATING.md) for details.
