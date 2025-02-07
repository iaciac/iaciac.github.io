---
title: Temporal group interactions in social systems
date: 2024-09-18
image:
  focal_point: 'top'
---

How do groups form and evolve? How do individuals navigate these group structures?

<!--more-->

Our study on **"The temporal dynamics of group interactions in higher-order social networks"**, together with [M. Karsai](https://www.martonkarsai.com/) and [A. Barrat](http://www.cpt.univ-mrs.fr/~barrat/), is out in *Nature Communications*! ----> [[link to arXiv](https://arxiv.org/abs/2306.09967)] - [[link to Nature Communications](https://www.nature.com/articles/s41467-024-50918-5)]

---
---

The structure and behaviour of many social systems are shaped by the **interactions among their individuals**. The typical approach in social network analysis consists in representing individuals as interacting in pairs, while **many human interactions involve groups** of many different sizes.

{{< figure src="drinks.jpeg" title="Ph by [Kier in Sight](https://unsplash.com/@kellysikkema)" width=700 >}}

Our everyday social path is in fact a succession of these **group events** that involve different numbers of peers, from walking alone or having a coffee with a friend, to engaging in meetings or group conversations at work or during social gatherings.

**Why do we care about groups?**

On the one hand, there is a **foundational reason**. To obtain meaningful insights from a system, choosing an appropriate representation is a crucial step that cannot be overlooked.
Since the building blocks of many ---not just social--- complex systems are intrinsically non-pairwise, there is often a need for higher-order approaches. Hypergraphs are thus natural candidates to [move system descriptions beyond dyadic relationships](https://doi.org/10.1016/j.physrep.2020.05.004) and effectively map relationships between any number of units (see also [this post](https://iaciac.github.io/post/beyond/)).

On the other hand, letting individuals interact in complex groups can have **phenomenological consequences**. Groups can lead to critical mass effects in [social contagion](https://www.nature.com/articles/s41467-019-10431-6) and [social dilemmas](https://arxiv.org/abs/2303.11475), [sustain epidemics](https://www.nature.com/articles/s42005-021-00788-w), [accelerate the formation of consensus](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.105.054307) and [help minorities of committed individuals to overturn the status quo](https://www.nature.com/articles/s42005-022-00845-y) (see also [this post](https://iaciac.github.io/post/group-interactions-modulate-critical-mass-dynamics-in-social-convention/)).

{{< figure src="grouping.jpeg" title="Ph by [Kier in Sight](https://unsplash.com/@kierinsight)" width=700 >}}

Recent **empirical studies** on [co-authorship data](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-017-0114-8), [face-to-face](https://www.nature.com/articles/s41598-021-86469-8), and [online](https://www.pnas.org/doi/10.1073/pnas.1800683115) interactions have shown that groups may appear in heterogeneous size (order), can [change dynamically](https://scholarship.richmond.edu/bookshelf/5/), or exhibit complex [hierarchical](https://www.nature.com/articles/s42005-022-00858-7) and [nested](https://arxiv.org/abs/2301.04235) structures. **Group size** is indeed a crucial factor that [determines a group's sociological form](https://www.journals.uchicago.edu/doi/abs/10.1086/211115) and its ability to sustain a single conversation ---leading to the phenomenon known as [schisming](https://psycnet.apa.org/record/1999-10015-001). 

Most studies on group formation and structure, however, do not take into account the temporal evolution of the underlying social systems, characterised by patterns of [memory](https://www.nature.com/articles/s41598-021-86469-8), [burstiness](https://www.nature.com/articles/s41598-023-32253-9), and [temporal correlations](https://arxiv.org/abs/2303.09316).
These complex patterns are **the results of microscopic individual-level decisions**, ultimately shaping the emergence of collective behaviours. 

Understanding these mechanisms ---**how these groups form, evolve**, and **how people move across groups**--- is essential to better characterise the emerging group dynamics and to better model biological contagion or transfer of social norms and information.

---

In this [new study](https://www.nature.com/articles/s41467-024-50918-5), together with [M. Karsai](https://www.martonkarsai.com/) and [A. Barrat](http://www.cpt.univ-mrs.fr/~barrat/), we study the temporal dynamics of groups through empirical traces of social interactions. Leveraging two publicly-available data sets of temporally-resolved human interactions among [preschool children](https://www.nature.com/articles/s41597-022-01756-x) and [university students](https://www.nature.com/articles/s41597-019-0325-x), we highlight complex mechanisms of group dynamics both at the node and at the group level.

At the **node level**, we follow how individuals move across groups of different sizes, finding that the main dynamical patterns of group-change are **independent from the nature and context of interactions** (due to age and setting constraints). 

{{< figure src="Fig1.png" title=" Group size distributions (*A*-*B*) and node transition matrices (*C*-*G*) for University and Preschool interactions that take place in-class, out-of-class, or during the weekend. In (*C*-*G*) the elements of each matrix represent the conditional probability $P(n_i^{t+1}=k^{\prime}|n_i^t=k)$ of finding a node $i$ in a group of size $k^{\prime}$ at time $t+1$ given that at time $t$ it belonged to a different group of size $k$. Probability values are given by the height of each element (normalized by row). Note that the scales on the y-axes--one for each matrix row--vary for visualization purposes." width=600 >}}

Shifting the focus to the groups, we analyze the statistics of **group duration**. Whether students interact during classes, in the other spaces of the university, or
elsewhere during the weekend, the distributions of their group interactions depend on the group size in a similar way, with _long-gets-longer_ effects.

{{< figure src="Fig2.png" title="Distributions of group durations $\tau$ for the University (*A*-*C*) and the Preschool (*D*-*E*) data sets in different contexts. Different symbols correspond to different group sizes." width=650 >}}

While the individual point of view adopted is useful to understand how people move between group sizes, we still need to understand the impact of these individual changes on the sizes of the groups. For instance, large groups tend to have shorter lives, but **how do they break up?** Similarly, **how do they grow?** Indeed, a group might appear due to the **fusion of two pre-existing groups of comparable sizes** ---like water droplets that merge after overlapping due to surface tension---, or from a **gradual process** due to the integration of one individual at a time.

{{< figure src="droplets.jpeg" title="Ph by [Leohoho](https://unsplash.com/@leohoho) " width=700 >}}

We thus follow the members of each group before the group’s birth and after its break-up, pooling together the results of groups of the same size. For **small group sizes, both group aggregation and disaggregation tend to happen gradually** from or to groups of similar sizes. The picture for larger groups suggests instead a **partially hierarchical dynamical mechanism** according to which individuals first engage in relatively small groups that then aggregate and form bigger ones. A symmetric process takes place when large groups dismantle.

{{< figure src="Fig3.png" title="Group dynamics of aggregation and disaggregation for University (*A*-*C*) and Preschool (*D*-*E*) interactions that take place during in-class, out-of-class, or weekend time. Each side of the pyramidal heatmaps shows the probability distribution associated to the size for the largest sub-group joining and the largest subgroup leaving a group of size $k$. The central column reports the considered group size $k$, while the probability distributions on its left-hand side and right-hand side respectively corresponds to group aggregation and disaggregation. Dashed lines refer to the distribution average." width=450 >}}

Finally, we propose a **synthetic hypergraph model** describing how nodes form groups and navigate between groups of different sizes. Informed by empirical data, the model reproduces the non-trivial dynamics of group changes, and could be used to generate synthetic substrates for **studying the impact of higher-order temporal interactions on dynamical processes**. 

{{< figure src="Fig5.png" title="Simulated distribution of group size, node transition matrix, and group duration for different group sizes $k$ generated by the proposed temporal hypergraph model (fitted on the University out-of-class setting)." width=450 >}}

Taken together, our results hint at common robust mechanisms determining group formation and evolution. Our study represent a further step in **understanding the social dynamics of higher-order interactions**, stressing the importance of considering their temporal aspect. 

---