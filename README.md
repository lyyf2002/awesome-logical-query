# awesome-logical-query-answering
A collection of resources on the topic of Complex Logical Query Answering

TODO: Insert an image from the paper

## :scroll: Categorization of papers

### Modalities


<details>
  <summary>Triple-based KGs (29)</summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  6. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  7. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  8. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  9. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  10. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  11. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  12. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  13. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  14. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  15. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  16. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  17. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  18. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  19. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  20. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  21. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  22. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  23. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  24. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  25. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  26. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  27. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  28. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  29. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

  </details> 

<details>
  <summary>Hyper-relational KGs (1)</summary>

  1. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022

</details>

<details>
  <summary>Hyper-graphs and Multi-modal graphs (0)</summary>

  0. None as of Sept 2022
  
</details>


### Reasoning Domain


<details>
  <summary>Discrete (Entities only) (29) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  6. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  7. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  8. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  9. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  10. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  11. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  12. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  13. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  14. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  15. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  16. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  17. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  18. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  19. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  20. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  21. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  22. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  23. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  24. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  25. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  26. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  27. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  28. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  29. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
</details>

<details>
  <summary>Predict Qualifier Entities for Hyper-Relational KGs (0)</summary>

  0. None as of Sept 2022
  
</details>
  
<details>
  <summary>Discrete Temporal (Entities + Dates) (1)</summary>

  1. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
  
</details>

<details>
  <summary>Discrete + Continuous (Entities + string/numerical Literals) (0)</summary>

  0. None as of Sept 2022
  
</details>



### Logical Expressiveness


<details>
  <summary>EPFO (16) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020    
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  6. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  9. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  10. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  14. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  15. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  16. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022

</details>

<details>
  <summary>EPFO + Negation queries (11) </summary>

  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  3. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  4. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  5. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  6. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  7. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  8. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  9. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  10. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  11. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
</details>

<details>
  <summary>Class / relation axioms (3) </summary>

  1. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  2. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  3. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
</details>


### Learning

<details>
  <summary>Transductive (28) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019  
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  6. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  7. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  8. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  9. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  10. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  14. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  15. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  18. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  19. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  20. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  21. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  22. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  23. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  24. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  25. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  26. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  27. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  28. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022
</details>

<details>
  <summary>Inductive (limited) (1) </summary>

  1. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022

</details>

<details>
  <summary>Inductive (2) </summary>

  #### Target Inductive (0)
  0. None as of Sept 2022

  #### Any node on the reasoning path inductive (2)
  1. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  2. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  

</details>


### Modeling

<details>
  <summary>End-to-end Neural (6) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  4. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  5. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  6. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022

</details>

<details>
  <summary>Neuro-Symbolic (19) </summary>

  #### GNN-based (3)
  1. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  2. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  3. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022

  #### Geometric (6)
  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020
  2. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  3. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  4. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  5. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  6. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022

  #### Distributions (3)
  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  3. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
   

  #### Entity-centric or T-norms (7)

  1. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  2. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  3. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  4. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  5. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  6. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  7. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary>Symbolic (3) </summary>

  1. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020   
  2. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  3. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022

</details>

### Training

<details>
  <summary> End-to-end trainable (29) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  6. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  7. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  8. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  9. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  10. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  11. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  12. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  13. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  14. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  15. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  16. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  17. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  18. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  19. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  20. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  21. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  22. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  23. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  24. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  25. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  26. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  27. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  28. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  29. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary> Inference-only (decoders) (1) </summary>

  1. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21

</details>


### Query Patterns

<details>
  <summary>Fixed patterns from specific datasets (25) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020  
  4. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  5. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  6. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  7. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  8. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  9.  [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  10. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  11. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  12. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  13. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  14. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  15. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  16. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  17. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  18. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022
  19. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  20. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  21. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  22. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  23. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  24. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  25. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary>Arbitrary query DAGs (4) </summary>

  1. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  2. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  3. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  4. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022

</details>

<details>
  <summary>Extended query DAGs (eg, hyper-relational) (1) </summary>

  1. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022

</details>

<details>
  <summary>Allowing cyclic query patterns (0) </summary>

  0. None as of Sept 2022

</details>

<details>
  <summary>Arbitrary query shapes (0) </summary>

  0. None as of Sept 2022

</details>


### Query Operators

Progressive scale of supported operators. That is, all models listed under the "NOT" category also support JOIN and UNION.

<details>
  <summary>PROJECTION + JOIN (intersection) (8) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019 
  3. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020
  4. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  5. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  6. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  7. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  8. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022

</details>

<details>
  <summary> + UNION (9) </summary>

  1. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020
  2. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  3. [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  4. [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  5. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021
  6. [CQD](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21
  7. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  8. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  9.  [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022

</details>

<details>
  <summary> + NOT (negation) (13) </summary>

  1. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  2. [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  3. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  4. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  5. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  6. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  7. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  8. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  9. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  10. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  11. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  12. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  13. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>

<details>
  <summary> + FILTER over discrete outputs (filtering entities) (0) </summary>

  0. None as of Sept 2022

</details>

<details>
  <summary> + FILTER over discrete + continuous outputs (+ filtering literals) (0) </summary>

  0. None as of Sept 2022

</details>

<details>
  <summary> + AGGREGATIONS (GROUP BY, ORDER BY, etc) (0) </summary>

  0. None as of Sept 2022

</details>


### Return Type (Projections)

<details>
  <summary> Final node only (7) </summary>

  1. [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf), NeurIPS 2018  
  2. [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA), ICDM 2019
  3. [MPQE](https://grlplus.github.io/papers/26.pdf), ICML 2020 Workshop
  4. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf), arxiv 2021
  5. [MLPMix](https://openreview.net/forum?id=tgcAoUVHRIB), ICLR 2022
  6. [StarQE](https://arxiv.org/abs/2106.08166), ICLR 2022
  7. [CBR-SUBG](https://proceedings.mlr.press/v162/das22a.html), ICML 2022

</details>

<details>
  <summary> Arbitrary non-anchor nodes (intermediate variables) (22) </summary>
 
  1. [TractOR](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020
  2. [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020  
  3. [BetaE](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020
  4. [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html), NeurIPS 2020
  5. [BiQE](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021
  6.  [CQD](https://openreview.net/forum?id=Mos9F9kDwkz), ICLR 2021
  7.  [HypE](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021
  8.  [NewLook](http://tonghanghang.org/pdfs/kdd21_newlook.pdf), KDD 2021
  9.  [ConE](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html), NeurIPS 2021
  10. [PERM](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html), NeurIPS 2021
  11. [Neural-symbolic Approach for Ontology-mediated Query Answering](https://arxiv.org/pdf/2106.14052.pdf), arxiv 2021
  12. [LogicE](https://arxiv.org/pdf/2103.00418.pdf), arxiv 2021
  13. [FuzzQE](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  14. [GNN-QE](https://arxiv.org/abs/2205.10128), ICML 2022
  15. [SMORE](https://arxiv.org/abs/2110.14890), KDD 2022
  16. [kgTransformer](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf), KDD 2022
  17. [LinE](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw), KDD 2022
  18. [Query2Particles](https://arxiv.org/abs/2204.12847), NAACL 2022
  19. [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591), arxiv 2022
  20. [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782), arxiv 2022
  21. [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039), arxiv 2022
  22. [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf), arxiv 2022

</details>



### Metrics

- Original metrics: ROC AUC and Average Percentile Rank over 1000 negative samples. 
  - Proposed by original [GQE](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf) (NeurIPS 2018), used by [GQE+hashing](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA) and [TractOR](https://arxiv.org/pdf/2002.10029.pdf). **Not used after**.
- Generalization: predicting hard answers (MRR / Hits@k).
  - Introduced by [Query2Box](https://openreview.net/pdf?id=BJgr4kSFDS) (ICLR 2020). **Standard metric**.
- Generalization: from ranking to binary classification
  - Proposed in [Approximate knowledge graph query answering: from ranking to binary classification](https://library.oapen.org/bitstream/handle/20.500.12657/48251/9783030723088.pdf?sequence=1#page=114)
- Entailment: faithfulness - ability to recover easy answers (no link prediction) (MRR / Hits@k)
  - Proposed by [EmQL](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html) (NeurIPS 2020)
- Estimating the cardinality of answer set size (Spearman's rank correlation, MAPE)
- Predicting easy answers before hard answers (ROC-AUC)


## 📈 Datasets and Benchmarking

### GQE Datasets

Are Bio and Reddit available at all? Introduced in GQE, used in 3 papers overall (GQE, GQE+hashing, TractOR).

### BetaE Datasets

The main difference with Query2Box datasets: queries in the BetaE datasets have less than 100 answers. Has queries with negation.

Introduced in [Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf), NeurIPS 2020

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | FB15k237 | 14,505 | 237   | 272,115 | 17,526 | 20,438 | 310,079 |
  | NELL995  | 63,361 | 200   | 114,213 | 14,324 | 14,267 | 142,804 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p/2p/3p/2i/3i  | 2in/3in/inp/pin/pni  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 27,371 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 14,968 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 10,798 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Average Number of Answers </summary>

  | Dataset | 1p | 2p |  3p | 2i |  3i | ip | pi | 2u | up | 2in | 3in | inp | pin | pni |
  |---------|---:|---:|----:|---:|----:|---:|---:|---:|---:|---:|----:|---:|---:|---:|
  | FB15k   | 1.7 | 19.6 | 24.4 | 8.0 | 5.2 | 18.3 | 12.5 | 18.9 | 23.8 | 15.9 | 14.6 | 19.8 | 21.6 | 16.9 |
  | FB15k237 | 1.7 | 17.3 | 24.3 | 6.9 | 4.5 | 17.7 | 10.4 | 19.6 | 24.3 | 16.3 | 13.4 | 19.5 | 21.7 | 18.2 |
  | NELL995 | 1.6 | 14.9 | 17.5 | 5.7 | 6.0 | 17.4 | 11.9 | 14.9 | 19.0 | 12.9 | 11.1 | 12.9 | 16.0 | 13.0 | 
  
</details>

### Query2Box Datasets

Introduced in [Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings](https://openreview.net/pdf?id=BJgr4kSFDS), ICLR 2020. 

EPFO queries are considered **easier** than BetaE datasets. Doesn't have queries with negations.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | FB15k237 | 14,505 | 237   | 272,115 | 17,526 | 20,438 | 310,079 |
  | NELL995  | 63,361 | 200   | 114,213 | 14,324 | 14,267 | 142,804 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p  | others  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 273,710 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 149,689 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 107,982 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Average Number of Answers </summary>

  | Dataset | 1p | 2p |  3p | 2i |  3i | ip | pi | 2u | up | 
  |---------|---:|---:|----:|---:|----:|---:|---:|---:|---:|
  | FB15k   | 10.8 | 255.6 | 250.0 | 90.3 | 64.1 | 593.8 | 190.1 | 27.8 | 227.0 | 
  | FB15k237 | 13.3 | 131.4 | 215.3 | 69.0 | 48.9 | 593.8 | 257.7 | 35.6 | 127.7 | 
  | NELL995 | 8.5 | 56.6 | 65.3 | 30.3 | 15.9 | 310.0 | 144.9 | 14.4 | 62.5 | 
  
</details>

### Regex Queries

Queries emulating property paths in SPARQL with variable length of relation paths (up to length 5). Queries are EPFO queries, i.e., no negation.
New operators over relations resemble those from SPARQL:
* $r_1 / r_2 / \dots$ - relational path, aka classic projection queries
* $r_1 \lor r_2$ - a union of decomposed patterns $(e, r_1, ?) \lor (e, r_2, ?)$
* Kleene plus $r^{+}$ - one or more occurence of relation $r$, eg, $r_1/r_2^{+}$ corresponds to $r_1 / r_2$, $r_1 / r_2 / r_2$, $r_1 / r_2 / r_2 / r_2 / \dots$ up to some final depth. Those *can* be cyclic patterns. 

Two datasets:

* FB15k-Regex is based on Freebase, queries have less than 50 answers, 21 query types
* Wiki100-Regex is based on query logs from the official Wikidata SPARQL endpoint, 5 query types. 

Introduced in [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480), AKBC 2021.

Repo: [GitHub](https://github.com/dair-iitd/kbi-regex) - no actual data dumps are present :(

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB15k    | 14,951 | 1,345 | 483,142 | 50,000 | 59,071 | 592,213 |
  | Wiki100 | 41,291 | 100   | 389,795 | 21,655 | 21,656 | 433,106 |


</details>

<details>
  <summary> Queries </summary>

  #### FB15k-Regex

  | Query type | Train | Valid | Test |
  |-----------:|------:|------:|-----:|
  |  $(e_1, r_1^+, ?)$    | 24,476 | 4,614 | 8,405 |
  |  $(e_1, r_1/r_2, ?)$  | 25,378 | 4,927  | 8,844 |
  | $(e_1, r_1^+/r_2^+, ?)$  | 26,391  | 4,978  | 9,028 |
  | $(e_1, r_1^+/r_2^+/r_3^+, ?)$ | 25,470  | 4,878 | 8,816 |
  | $(e_1, r_1/r_2^+, ?)$  | 26,335 | 5,007 | 9,062 |
  | $(e_1, r_1^+/r_2, ?)$  | 27,614 | 5,229 | 9,429 |
  | $(e_1, r_1^+/r_2^+/r_3, ?)$ | 27,865 | 5,283 | 9,509 |
  | $(e_1, r_1^+/r_2/r_3^+, ?)$ | 26,366 | 5,058 | 9,159 |
  | $(e_1, r_1/r_2^+/r_3^+, ?)$ | 26,366 | 5,045 | 9,099 |
  | $(e_1, r_1/r_2/r_3^+, ?)$   | 26,703 | 5,155 | 9,313 |
  | $(e_1, r_1/r_2^+/r_3, ?)$   | 28,005 | 5,380 | 9,688 |
  | $(e_1, r_1^+/r_2/r_3, ?)$   | 27,884 | 5,338 | 9,632 |
  | $(e_1, r_1\lor r_2, ?)$ | 30,080 | 5,828 | 9,664 |
  | $(e_1, (r_1\lor r_2)/r_3, ?)$ | 31,559 | 6,606 | 10,974 |
  | $(e_1, r_1/(r_2\lor r_3), ?)$ | 41,886 | 7,755 | 13,611 |
  | $(e_1, r_1^+\lor r_2^+, ?)$   | 23,109 | 4,469 | 8,367  |
  | $(e_1, (r_1\lor r_2)/r_3^+, ?)$ | 27,658 | 5,738 | 9,711 |
  | $(e_1, (r_1^+\lor r_2^+)/r_3, ?)$ | 24,462 | 4,865 | 8,863 |
  | $(e_1, r_1^+/(r_2\lor r_3), ?)$ | 27,676 | 5,340 | 9,267 |
  | $(e_1, r_1/(r_2^+\lor r_3^+), ?)$ | 28,542 | 5,475 | 9,436 |
  | $(e_1, (r_1\lor r_2)^+, ?)$  | 26,260 | 5,523 | 10,360 |
  |  **Total**                   | 580,085 | 112,491 | 200,237 |


  #### Wiki100-Regex

  | Query type | Train | Valid | Test |
  |-----------:|------:|------:|-----:|
  |  $(e_1, r_1^+, ?)$    | 490,562 | 24,878 | 23,443 |
  | $(e_1, r_1^+/r_2^+, ?)$  | 6,945  | 620  | 772 |
  | $(e_1, r_1/r_2^+, ?)$  | 85,253 | 10,013 | 8,377 |
  | $(e_1, r_1\lor r_2, ?)$ | 274,012 | 14,900 | 14,915 |
  | $(e_1, (r_1\lor r_2)^+, ?)$  | 348,274 | 15,720 | 15,311 |
  |  **Total**                   | 1,205,046 | 66,131 | 62,818 |

</details>

### DAG Queries

Conjunctive queries (w/o union) not limited to 9 patterns from Query2Box/BetaE datasets. The task is to predict *all* intermediate entities, not just final leaf nodes. Query depth: 2-5; max 3 intersecting branches.

Introduced in [Answering complex queries in knowledge graphs with bidirectional sequence encoders](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI 2021.

New FB15K-237-CQ and WN18RR-CQ datasets have two variations:
* CQ (conjunctive queries) - Training on triples + paths + DAGs, Validation/Test on **DAGs only**;
* Paths - Training on triples + paths, Validation/Test on **paths only**

**Sept 2022: the datasets are not publicly available.**

<details>
  <summary> Graphs </summary>
  
  | Dataset | FB15K-237-CQ | FB15K-237-CQ | FB15K-237-CQ | WN18RR-CQ | WN18RR-CQ | WN18RR-CQ |
  |-----|----:|----:|----:|----:|----:|----:|
  | Dataset | Train | Validation | Test | Train | Validation | Test |
  | Entities | 14,505 | - | - | 40,943 | - | - |
  | Relations | 237 | 237 | 237 | 11 | 11 | 11 |
  | Triples  | 272,115 | - | - | 86,835 | - | - |
  | Paths | 50,000 | - | - | 10,000 | - | - |
  | DAGs | 48,865 | 2,785 | 2,599 | 9,465 | 112 | 95 |
  | Avg Masks | 1.86 | 5.91 | 6.05 | 1.84 | 5.13 | 4.91 |
  | Avg Query Len (Tokens) | 152 | 460 | 479 | 71 | 198 | 199 |   


</details>

<details>
  <summary> Queries </summary>
  
  No detailed breakdown by query type is available, only the DAGs stats from the main table.

  | Dataset | FB15K-237-CQ | FB15K-237-CQ | FB15K-237-CQ | WN18RR-CQ | WN18RR-CQ | WN18RR-CQ |
  |-----|----:|----:|----:|----:|----:|----:|
  | Dataset | Train | Validation | Test | Train | Validation | Test |
  | Paths | 50,000 | - | - | 10,000 | - | - |
  | DAGs | 48,865 | 2,785 | 2,599 | 9,465 | 112 | 95 |
  | Avg Masks | 1.86 | 5.91 | 6.05 | 1.84 | 5.13 | 4.91 |
  | Avg Query Len (Tokens) | 152 | 460 | 479 | 71 | 198 | 199 | 

</details>

###  EFO-1 Queries

Existential First-Order queries  with Singel Free Variable, extended from BetaE. The goal is to evaluate the combinatorial generalizability. 

Introduced in [Benchmarking the Combinatorial Generalizability of Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08925), NeurIPS 2021 (Datasets and Benchmarks)

<details>
  <summary> Graphs </summary>

  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p/2p/3p/2i/3i  | 2in/3in/inp/pin/pni  | 1p | others | 1p | others |
  | FB15k    | 273,710 | 27,371 | 59,097 | 8,000 | 67,016 | 8,000 |
  | FB15k237 | 149,689 | 14,968 | 20,101 | 5,000 | 22,812 | 5,000 |
  | NELL995  | 107,982 | 10,798 | 16,927 | 4,000 | 17,034 | 4,000 | 

</details>

<details>
  <summary> Queries </summary>

Cannot list all the 301 query types. Details can be found in a summarization excel file [here](https://docs.google.com/spreadsheets/d/18RJL1puHpbGZJKLkffqKEbzRmRFdSnGFQvekApFWc3Q/edit?usp=sharing).

</details>

### Type-Aware Datasets

In addition to a normal graph of entities (instances) a-la BetaE datasets, the type-aware datasets offer an additional set of classes, classes hierarchy (from a pre-existing ontology), and `instanceOf` links between entities and classes.

Those datasets might include an additional task of predicting types of answer entities (Concept Retrieval).

- LUBM, introduced in [Neuro-Symbolic Ontology-Mediated Query Answering](https://openreview.net/pdf?id=wwVb95CkrFm), OpenReview 2021
- NELL, introduced in [Neuro-Symbolic Ontology-Mediated Query Answering](https://openreview.net/pdf?id=wwVb95CkrFm), OpenReview 2021. The base graph is the same as in the BetaE datasets, but a few ontological axioms were added.
- YAGO 4, introduced in [TAR: Neural Logical Reasoning across TBox and ABox](https://github.com/lilv98/TAR)
- DBpedia, introduced in [TAR: Neural Logical Reasoning across TBox and ABox](https://github.com/lilv98/TAR)

LUBM and NELL employ ontological axioms of the DL-Lite (R) family of Description Logics.

<details>
  <summary> Graphs </summary>

  **TODO** Figure out Concept Retrieval edges in TAR 
  
  | Dataset | Entities | Relations | Axioms | Base Graph | Materialized Graph | 
  |-----|----:|----:|----:|----:|----:|
  | LUBM | 55,684 | 28 | 68 | 284k | 565k | 
  | NELL | 63,361 | 400 | 307 | 285k | 497k | 

  Axioms breakdown in ontologies for LUBM and NELL

  | Rules | LUBM | NELL | 
  |------:|-----:|-----:|
  | $\mathcal{O}$ (Total) |  68  | 307  |
  | $A \sqsubseteq A'$ (Subclass) | 13 | - |
  | $p \sqsubseteq s$ | 5 | 92 |
  | $p^{-} \sqsubseteq s$ | 28 | 215 |
  | $\exists p \sqsubseteq A$ | 11 | - |
  | $\exists p^{-} \sqsubseteq A$ | 11 | - |



  | Dataset | Entities | Relations | Classes | Training Edges | Validation Edges | Test Edges | Entity-Class Edges | Class Hierarchy Edges | Total Edges |
  |-----|----:|----:|----:|----:|----:|----:|---:|---:|---:|
  | YAGO 4 | 32,465 | 75 | 8,382 | 101,417 | 1,000 | 1,000 | 83,291 | 16,644 | 184,708 |
  | DBpedia | 28,824 | 327 | 981 | 136,821 | 1,000 | 1,000 | 225,436 | 2,582 | 362,257 |
  


</details>

<details>
  <summary> Queries </summary>
  
  | Dataset | Train / Test | 1p | 2p | 3p | 2i | 3i | ip | pi | 2u | up |
  |--------:|-------------:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
  | LUBM    | Plain (**Train**)| 110,000 | 110,000 | 110,000 | 110,000 | 110,000 | - | - | - | - |
  | LUBM    | Generalized (**Train**)| 117,124 | 136,731 | 150,653 | 181,234 | 208,710 | - | - | - | - | 
  | LUBM    | Specialized (**Train**)| 117,780 | 154,851 | 173,678 | 271,532 | 230,085 | - | - | - | - | 
  | LUBM    | Ontological (**Train**)| 116,893 | 166,159 | 333,406 | 212,718 | 491,707 | - | - | - | - |
  | LUBM    | Induction (w/ missing links in queries) (**Val/Test**)| 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 
  | LUBM    | Deduction (w/o missing link in training) (**Val/Test**)| 1,241 | 4,701 | 6,472 | 3,829 | 4,746 | 7,393 | 7,557 | 4,986 | 7,122 |
  | LUBM    | Induction + Deduction (**Val/Test**)| 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 7,986 | 8,000 |
  | NELL    | Plain (**Train**)| 107,982 | 107,982 | 107,982 | 107,982 | 107,982 | - | - | - | - |
  | NELL    | Generalized (**Train**)| 174,310 | 408,842 | 864,268 | 398,412 | 930,787 | - | - | - | - | 
  | NELL    | Specialized (**Train**)| 174,310 | 419,664 | 906,609 | 401,954 | 936,537 | - | - | - | - | 
  | NELL    | Ontological (**Train**)| 114,614 | 542,923 | 864,268 | 629,144 | 930,787 | - | - | - | - |
  | NELL    | Induction (w/ missing links in queries) (**Val/Test**)| 15,688 | 3,910 | 3,918 | 3,828 | 3,786 | 3,932 | 3,895 |3,940 | 3,966 | 
  | NELL    | Deduction (w/o missing link in training) (**Val/Test**)| 346 | 4,461 | 4,294 | 4,842 | 5,996 | 7,295 | 5,862 | 5,646 | 6,894 |
  | NELL    | Induction + Deduction (**Val/Test**)| 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 8,000 | 7,990 | 8,000 |


  | Queries | Training | Training |  Validation | Validation |  Test | Test |
  |---------|---------:|-----------:|-----:|---------:|-----------:|-----:|
  | Dataset | 1p  | others  | 1p | others | 1p | others |
  | YAGO 4 (Concept Retrieval)    | 189,338 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | YAGO 4 (Entity Only)    | 101,417 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | YAGO 4 (Entity + Instantiations)    | 184,708 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | DBpedia (Concept Retrieval)    | 473,924 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | DBpedia (Entity Only)    | 136,821 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |
  | DBpedia (Entity + Instantiations)    | 362,257 | 10,000 | 1,000 | 1,000 | 1,000 | 1,000 |



</details>

### Very Large Datasets

Introduced in [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890), KDD 2022.

Training queries are sampled on-the-fly during training due to the huge size of underlying graphs. 

The underlying graphs are FB400k (400K nodes), WikiKG 2 (2.5M nodes) [(from OGB)](https://ogb.stanford.edu/docs/linkprop/#ogbl-wikikg2), and full Freebase (86M nodes)
TODO: confirm with Hongyu the number of validation / test queries.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|
  | FB400k    | 409,829 | 918 | 1,075,837 | 537,917 | 537,917 | 2,151,671 |
  | WikiKG2 | 2,500,604 | 535   | 16,109,182 | 429,456 | 598,543 | 17,137,181 |
  | Freebase  | 86,054,361 | 14,824  | 304,727,650 | 16,929,318 | 16,929,308 | 338,586,276 | 

</details>

<details>
  <summary> Queries </summary>

  | Queries |  Validation | Validation |  Test | Test |
  |---------|------------:|-----------:|------:|-----:|
  | Dataset |  1p | others | 1p | others |
  | FB400k    | TODO | TODO | TODO | TODO |
  | WikiKG2 | TODO | TODO | TODO | TODO |
  | Freebase  | TODO | TODO | TODO | TODO |

</details>

### Hyper-Relational Datasets

The main difference of hyper-relational datasets is that edges are no longer plain triples $(h, r, t)$ but *statements* (in terms of Wikidata) $\Big(h, r, t, (q\_{ri}, q\_{ei})\_i\Big)$ with key-value (relation:entity) qualifiers $(q\_{r}, q\_{e})$ over the *main* triple.

Entities and relations in qualifiers are still legit entities and relations which could be present in main triples. Still, some entities and relations can be found *only* in qualifiers.

The dataset has only conjunctive queries (projection + intersection), neither union nor negation.

Introduced in [Query Embedding on Hyper-Relational Knowledge Graphs](https://openreview.net/pdf?id=4rLw09TgRw9), ICLR 2022

<details>
  <summary> Graph </summary>

  The original WD50K graph from the [StarE paper](https://aclanthology.org/2020.emnlp-main.596.pdf) by Galkin et al.


  | Dataset | Entities | Relations | Qualifier-only Entities | Qualifier-only Relations | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|----:|----:|
  | WD50K    | 47,156 | 532 | 5460 | 45 | 166,435 | 23,913 | 46,159 | 236,508 |

  32,167 edges have at least one key-value (relation:entity) qualifier.
 

</details>

<details>
  <summary> Queries </summary>

  | Split | 1p | 2p | 3p | 2i | 3i | ip | pi |
  |-----|----:|----:|----:|----:|----:|----:|----:|
  | train | 24,819 | 313,088 | 5,950,990 | 48,513 | 318,735 | 306,022 | 1,088,539 |
  | validation | 4,100 | 100,706 | 2,968,315 | 15,648 | 169,195 | 169,438 | 569,957 |
  | test  | 7,716 | 202,045 | 6,433,476 | 38,207 | 547,272 | 445,007 | 1,267,452 |


</details>

### Inductive Datasets


### Temporal Datasets

Introduced in [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/abs/2205.14307), KDD 2022.

Based on FOL operators, the dataset focuses on temporal reasoning, which includes `after`, `before` and `between` on any timestamp set.

<details>
  <summary> Graphs </summary>

  | Dataset | Entities | Relations | Timestamps | Training Edges | Validation Edges | Test Edges | Total Edges
  |-----|----:|----:|----:|----:|----:|----:|----:|
  | ICEWS14 | 7,128 | 230 | 365 | 72,826 | 8,941 | 8,963 | 90,730 |
  | ICEWS05-15 | 10,488 | 251 | 4,017 | 386,962 | 46,275 | 46,092 | 479,329 |
  | GDELT-500  | 500 | 20 | 366 | 2,735,685 | 341,961 | 341,961 | 3,419,607 |

</details>

<details>
  <summary> Queries </summary>
  
| Query Name | ICEWS14-Train | Validation | Test | ICES05-15-Train | Validation | Test  | GDELT-500-Train | Validation | Test  |
|------------|---------------|------------|------|-----------------|------------|-------|-----------------|------------|-------|
| Pe2        | 72826         | 3482       | 4037 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| Pe3        | 72826         | 3492       | 4083 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| Pe_Pt      | 7282          | 3385       | 3638 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2i        | 72826         | 3305       | 3655 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| e3i        | 72826         | 2966       | 3023 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| e2i_Pe     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_e2i     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_t2i     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| e2i_NPe       | 7282          | 3061       | 3192 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2i_peN       | 7282          | 2971       | 3031 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_e2i_Pe_NPe | 7282          | 2968       | 3012 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2i_N         | 7282          | 2949       | 2975 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e3i_N         | 7282          | 2913       | 2914 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| e2u           | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_e2u        | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pt_lPe     | 7282          | 4976       | 5608 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pt_rPe     | 7282          | 3321       | 3621 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i        | 72826         | 5112       | 6631 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| t3i        | 72826         | 3094       | 3296 | 368962          | 10000      | 10000 | 2215309         | 10000      | 10000 |
| t2i_Pe     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pt_le2i    | 7282          | 3226       | 3466 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pt_re2i    | 7282          | 3236       | 3485 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i_NPt         | 7282          | 4873       | 5464 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i_PtN         | 7282          | 3300       | 3609 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_t2i_PtPe_NPt | 7282          | 3031       | 3127 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2i_N           | 7282          | 3135       | 3328 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t3i_N           | 7282          | 2924       | 2944 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| t2u        | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_t2u     | -             | 2913       | 2913 | -               | 10000      | 10000 | -               | 10000      | 10000 |
| Pe_aPt     | 7282          | 4134       | 4733 | 68262           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_bPt     | 7282          | 3970       | 4565 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_at2i    | 7282          | 4607       | 5338 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| Pe_bt2i    | 7282          | 4583       | 5386 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |
| between    | 7282          | 2913       | 2913 | 36896           | 10000      | 10000 | 221530          | 10000      | 10000 |

</details>

### Dataset tools

- [Graph Query Sampler](https://github.com/miselico/graph_query_sampler): Not a method, rather a dataset generator


## :wrench: Implementations

- [KGReasoning](https://github.com/snap-stanford/KGReasoning): GQE, Query2Box, BetaE
- [CQD](https://github.com/pminervini/KGReasoning): GQE, Query2Box, BetaE, CQD
- [StarQE](https://github.com/DimitrisAlivas/StarQE): StarQE
- [SMORE](https://github.com/google-research/smore): GQE, Query2Box, BetaE + Very Large Datasets
- [GNN-QE](https://github.com/DeepGraphLearning/GNN-QE): GNN-QE
- [TAR](https://github.com/lilv98/TAR): Former ABIN


## All Papers (33)

<details>
  <summary>Click to expand </summary>

  1. (GQE) [Embedding Logical Queries on Knowledge Graphs](https://proceedings.neurips.cc/paper/2018/file/ef50c335cca9f340bde656363ebd02fd-Paper.pdf) NeurIPS 2018
  2. (GQE + hashing) [Learning to Hash for Efficient Search over Incomplete Knowledge Graphs](https://ieeexplore.ieee.org/abstract/document/8970688/?casa_token=gLHFmr7V2ekAAAAA:wwDbUufdkwHTQo68pansuhJsJ2XQAF0P21_mQSu75KVRUkgqARmXBs_VEmFOkFgz_Lq-FXP8OA) ICDM’19
  3. (TractOR) [Symbolic querying of vector spaces: Probabilistic databases meets relational embeddings](https://arxiv.org/pdf/2002.10029.pdf), UAI 2020
  4. (Query2Box) [Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings](https://openreview.net/pdf?id=BJgr4kSFDS) ICLR 2020
  5. (BetaE) [Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs](https://proceedings.neurips.cc/paper/2020/file/e43739bba7cdb577e9e3e4e42447f5a5-Paper.pdf) NeurIPS 2020
  6. (EmQL) [Faithful embeddings for knowledge base queries](https://proceedings.neurips.cc/paper/2020/hash/fe74074593f21197b7b7be3c08678616-Abstract.html) NeurIPS 2020
  7. (MPQE) [Message Passing Query Embedding](https://grlplus.github.io/papers/26.pdf) ICML’20 Workshop
  8. [Regex Queries over Incomplete Knowledge Bases](https://arxiv.org/abs/2005.00480) AKBC’21
  9. (BiQE) [Answering complex queries in knowledge graphs with bidirectional sequence encoders](https://ojs.aaai.org/index.php/AAAI/article/view/16630), AAAI’21 
  10. [Approximate knowledge graph query answering: from ranking to binary classification](https://library.oapen.org/bitstream/handle/20.500.12657/48251/9783030723088.pdf?sequence=1#page=114) ← benchmarking, 2020 / 2021
  11. [Knowledge Sheaves: A Sheaf-Theoretic Framework for Knowledge Graph Embedding](https://arxiv.org/pdf/2110.03789.pdf) arxiv, BetaE datasets, 2021
  12. (ConE) [Cone: Cone embeddings for multi-hop reasoning over knowledge graphs](https://proceedings.neurips.cc/paper/2021/hash/a0160709701140704575d499c997b6ca-Abstract.html) NeurIPS’21
  13. (PERM) [Probabilistic entity representation model for reasoning over knowledge graphs](https://proceedings.neurips.cc/paper/2021/hash/c4d2ce3f3ebb5393a77c33c0cd95dc93-Abstract.html) (improv over BetaE) NeurIPS’21
  14. (CQD) [Complex Query Answering with Neural Link Predictors](https://openreview.net/forum?id=Mos9F9kDwkz) ICLR’21
  15. (HypE) [Self-Supervised Hyperboloid Representations from Logical Queries over Knowledge Graphs](https://dl.acm.org/doi/abs/10.1145/3442381.3449974?casa_token=tQx20rBUtMwAAAAA:GRqp4JBze6ybzZzeSdCc9cNGlqN0wkAP0BVBPctAgtUVviVSoNiUQcNxBbEuGVGZxnCzJyLqfMmiYg), WWW 2021 + (new) DBpedia + Amazon prod dataset
  16. (NewLook) [Neural-Answering Logical Queries on Knowledge Graphs](http://tonghanghang.org/pdfs/kdd21_newlook.pdf) (KDD’21) ← subgraph matching
  17. [Benchmarking the Combinatorial Generalizability of Complex Query Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08925), NeurIPS 2021 (Datasets and Benchmarks) ← benchmarking, 2021, new datasets
  18. [Neuro-Symbolic Ontology-Mediated Query Answering](https://openreview.net/pdf?id=wwVb95CkrFm) OpenReview 2021 (Q2B with rules), new datasets with types - LUBM + NELL
  19. (LogicE) [Logic Embeddings for Complex Query Answering](https://arxiv.org/pdf/2103.00418.pdf) arxiv 2021
  20. (StarQE) [Query Embedding on Hyper-relational Knowledge Graphs](https://arxiv.org/abs/2106.08166) ICLR 2022, new datasets
  21. (MLPMix) [Neural Methods for Logical Reasoning over Knowledge Graphs](https://openreview.net/forum?id=tgcAoUVHRIB) ICLR 2022
  22. (FuzzQE) [Fuzzy Logic Based Logical Query Answering on Knowledge Graphs](https://ojs.aaai.org/index.php/AAAI/article/view/20310), AAAI 2022
  23. (GNN-QE)  [Neural-Symbolic Models for Logical Queries on Knowledge Graphs](https://arxiv.org/abs/2205.10128), ICML 2022
  24. (CBR-SUBG) [Knowledge base question answering by case-based reasoning over subgraphs](https://proceedings.mlr.press/v162/das22a.html) ICML 2022 ← entailment only, custom datasets
  25. (SMORE) [SMORE: Knowledge Graph Completion and Multi-hop Reasoning in Massive Knowledge Graphs](https://arxiv.org/abs/2110.14890) KDD 2022 ← very large graphs, new datasets
  26. (kgTransformer) [Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries](https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD22-Liu-et-al-KG-Transformer.pdf) KDD 2022, old Q2B datasets
  27. (Query2Particles) [Query2Particles: Knowledge Graph Reasoning with Particle Embeddings](https://arxiv.org/abs/2204.12847), Findings NAACL’22
  28. (TAR) [TAR: Neural Logical Reasoning across TBox and ABox](https://arxiv.org/abs/2205.14591) (arxiv, 2022) Class Hierarchy, new dataset
  29. (TeMP) [Type-aware embeddings for multi-hop reasoning over knowledge graphs](https://arxiv.org/abs/2205.00782) (arxiv 2022) Class Hierarchy, new dataset
  30. (FLEX) [FLEX: Feature-Logic Embedding Framework for CompleX Knowledge Graph Reasoning](https://arxiv.org/abs/2205.11039) (arxiv 2022)
  31. (TFLEX) [TFLEX: Temporal Feature-Logic Embedding Framework for Complex Reasoning over Temporal Knowledge Graph](https://arxiv.org/pdf/2205.14307.pdf) (arxiv, 2022), new dataset
  32. (LinE) [LinE: Logical Query Reasoning over Hierarchical Knowledge Graphs](https://dl.acm.org/doi/pdf/10.1145/3534678.3539338?casa_token=_jPlNJj2TlYAAAAA:pKAA42_lrZ2JIHc1YZV0fchIlRiIcqCy8oCBL2UU3Gm84MOeTSYLfQn31DKtXBbU2yqzC7LUsYvREBw) KDD 2022
  33. GNNQ: A Neuro-Symbolic Approach for Query Answering over Incomplete Knowledge Graphs. Accepted to ISWC 2022, not yet available

</details>
