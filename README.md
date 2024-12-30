# Understanding Oversmoothing in Diffusion-Based GNNs From the Perspective of Operator Semigroup Theory

This repository contains the code for **"Understanding Oversmoothing in Diffusion-Based GNNs From the Perspective of Operator Semigroup Theory"**, which is primarily based on the [GREAD](https://github.com/jeongwhanchoi/GREAD) framework.

## Usage

To use the implementation:

1. Clone the original [GREAD GitHub Repository](https://github.com/jeongwhanchoi/GREAD):
   ```bash
   git clone https://github.com/jeongwhanchoi/GREAD.git
2. Replace the `function_gread.py` and `gread_params.py` files in the original repository with the `function_gread.py` and `gread_params.py` provided in this repository
3. Run the program and specify the desired breaking term during runtime. For instance: To run each experiment, navigate into src. Then, run the following command:
    ```
    python run_GNN.py --dataset=texas --use_best_params
    ```

## Citation
```
@article{zhao2024understanding,
  title={Understanding Oversmoothing in Diffusion-Based GNNs From the Perspective of Operator Semigroup Theory},
  author={Zhao, Weichen and Wang, Chenguang and Wang, Xinyan and Han, Congying and Guo, Tiande and Yu, Tianshu},
  journal={arXiv preprint arXiv:2402.15326},
  year={2024}
}

```