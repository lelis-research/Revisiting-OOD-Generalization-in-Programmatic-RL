# Revisiting OOD Generalization in Programmatic RL 

This is the implementation for "Revisiting OOD Generalization in Programmatic RL" paper, accepted at ICML 2026. For more info visit [project page](https://lelis-research.github.io/Revisiting-OOD-Generalization-in-Programmatic-RL/). This repository serves as an umbrella for all code implementations and experimental results related to our research. The work is organized into four dedicated submodules, each focusing on a specific environment or set of experiments:

- [SparsePolicies](https://github.com/lelis-research/Sparse-Policies/tree/fd8a2c4d100822200d1d3766f0c973ec0d460fe9): Core implementations and experiments related to `Karel`, `SparseMaze`, `Cartpole`, `Quad`, and `ParallelPark` environments.
- [SparsePolicies_Torcs](https://github.com/Amirhossein-Rajabpour/myTORCS-docker/tree/9114844bdc0c1cfdcfe7f4e3117b66b99225d66b): Experiments related to the [`Torcs`](https://sourceforge.net/projects/torcs/) environment. This repository uses a Dockerized version (also Apptainer for Compute Canada) of the Torcs server.
- [SparsePolicies_ParallelPark](https://github.com/lelis-research/neurips-2025-paper-neural-decomposition/tree/fa8e7d7fa9975431149a4d000dc11f7ee6d0aee7): Additional experiments for the `ParallelPark` environment.
- [FunSearch](https://github.com/Amirhossein-Rajabpour/Funsearch/tree/fe236f0132d1fa5aee47a935998438c11b298611): Using [this approach](https://deepmind.google/discover/blog/funsearch-making-new-discoveries-in-mathematical-sciences-using-large-language-models/) for finding programmatic policies for the `SparseMaze` environment.




<br>

### Usage

After cloning this super-project, initialize and update all submodules with:

```bash
git submodule update --init --recursive
```
Each submodule can then be accessed and run according to its own documentation and setup instructions.


 <br>

 ### Cite the paper (arXiv version for RLC 2025 workshop)
 ```
 @misc{rajabpour2025commonbenchmarksundervaluegeneralization,
      title={Common Benchmarks Undervalue the Generalization Power of Programmatic Policies}, 
      author={Amirhossein Rajabpour and Kiarash Aghakasiri and Sandra Zilles and Levi H. S. Lelis},
      year={2025},
      eprint={2506.14162},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2506.14162}, 
}
 ```

<br>

 ### Authors
 [Amirhossein Rajabpour](http://amirhossein-rajabpour.github.io/), [Kiarash Aghakasiri](https://scholar.google.co.uk/citations?user=UsE3he0AAAAJ&hl=en), [Sandra Zilles](https://www2.cs.uregina.ca/~zilles/), [Levi Lelis](https://webdocs.cs.ualberta.ca/~santanad/) 

 
