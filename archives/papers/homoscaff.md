## Knowledge gained
- All cycles on the sphere can be continuously transformed into each other and belong to the same homology class
- clique = completely connected subgraph contained in an undirected and unweighted graph
- k-simplex is the simplest possible polytope in the kth dimension, it is oriented if the order of its vertices are fixed in which switching two vertices introduces a minus sign
- oriented simplices represent actions: $[a, b] + [b, a] = [a,b] - [a,b] = 0$ 
- simplicial complex = a set of simplices attached together
- simplicial complex chains $C_p (\vec{K})$ = set of all possible p-chains generated from $\vec{K}$ 
- clique complex $\mathit{l}(G)$ = simplicial complex made of k-cliques represented as (k-1)-simplices
- cycle = non-empty trail in which first and last vertices are equal
- tree = connected graph without cycles
- $(S^1)^2$ = $\{(v,w) \in \mathbb{R}^{1+1+2} \quad | \quad v \in S^1, w \in S^1\}$
- ring = multiplication need not be commutative and multiplicative inverses need not exist
- module = generalisation vector space over a ring rather than field
- $\partial D^n = S^{n-1}, \quad \partial [a, b, c] = [b, c] + [c, a] + [a, b], \quad \partial: C_1 \rightarrow C_0$
- metric satisfies non-negativity, triangularity, symmetry, and separation
- boundary = combination of simplices that forms the boundary of higher-dimensional simplex
- $\beta_k = \text{rank}(H_k(S))$ = kth Betti number = number of k-dimensional holes on a topological surface, of which b0 measures n connected components, b1 n holes, b2, n cavities
- [k-dimensional holes bounded by (k-1) dimensional faces
- regions of reduced connectivity are holes, as when 3-cliques are filled in they become tiles
- convex hull = shape enclosed by rubber band stretched around subset, or smallest convex set that contains it
- [convex set = set that contains whole line segment between any two of its elements
- network becomes abstract simplicial complex topological space, with each element and face a simplex
- directed flag complex is abstract simplicial complex
- [maximal element not a face of any simplex of K except itself
- union of all sets in the sequence is the entire space in filtration
- filtration = $\{K_{\omega}\}$ as $K_{\omega} \subseteq K_{\omega}'$ for $\omega > \omega'$ when filtering through weights in descending order
- persistence  $\pi_g = \beta_g - \delta_g$ = birth - death of a hole in filtration; greater persistence = greater importance
- persistence diagram can highlight differences between two datasets
- persistence homological scaffold = network composed of all cycle paths connected by edges weighted by (sum of) persistence, whereas for frequency weight is number of different cycles it belongs to
- edge represents locally strong bridge if it has large total persistence --> stable hub links
- each hole is of a seperate equivalence class so unique generators assigned
- psilocybin distribution long tail --> few long lived cycles + different local functional structure
- certain cycles especially stable and only present in psychedelic state
- psilocybin ascribes cognition a more flexible quality
- more heavy links in psilo --> greater integration
- edges that change in significance tend to connect cortical regions --> emergence of strong, topologically long range functional connections --> synaesthesia
- worse colour perception on psilocybin
#### Abstract:
- [x] mesoscopic
- [ ] degree distribution, node centrality, modularity
- [ ] topological objects
- [ ] homological cycles and scaffolds
- [ ] correlation network
- [ ] weighted functional network
#### Motivation
- [ ] coherence
- [x] signed weighted adjacency matrices
- [ ] network homology
- [ ] 4d torus visualisation
- [ ] external direct product of a group
#### From networks to topological spaces and homology:
- [ ] formalise by opposition
- [ ] stratigraphy
- [ ] 2b graph formation?
#### A persistent homology of weighted networks
- [ ] flag complex
- [ ] k-dimensional cycle in the homology group Hk
#### Homological scaffolds
- [ ] equivalence class
- [ ] 0-chains
- [ ] generator and its cycle
- [ ] in itself, therefore the scaffolds are not topological invariants.
- [ ] edge added to a cycle after birth may create a triangle with the two edges composing the cycle --> misattribution
- [ ] properties of boundary operators
#### Results from fMRI networks
- [ ] covary out the variance
- [ ] Kolmogorov-Smirnov statistics
#### Discussion
- [ ] Why the cutoff 80
- [ ] Louvain method
- [ ] derivation of each conclusion from analysis
- [ ] grapheme
#### Methods
- [ ] FMRIB linear/ boundary-based registration
- [ ] 6/24 dimensional parameter time course
- [ ] Volterra expansion
- [ ] regressing motion
- [ ] Destrieux atlas FREESURFER tool
- [ ] Python Holes, javaplex integration using Jython
- [ ] persistence probability densities for H1 cycles
- [ ] segmented into 194 cortical + subcortical regions
- [ ] partial correlations
- [ ] non neural time courses discarded
## Further reading
- [(1)] 