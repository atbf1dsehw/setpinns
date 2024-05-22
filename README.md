# SetPINNs

SetPINNs offer a new approach to PINNs, demonstrating that processing neighboring points in the physical domain together can lead to accurate and robust results.

In this repository, we provide code and a demo on how to execute SetPINNs.

Refer to `src/` for the code.

Refer to `setpinns.ipynb` for a demo.

This pipeline is fully inspired by the PINNsFormer implementation, and we have utilized the assets provided by them on: [https://github.com/AdityaLab/pinnsformer](https://github.com/AdityaLab/pinnsformer). Please refer to their GitHub repository to acquire/use them.


We also present a comparison between PINNsFormer and SetPINNs. Please refer to `pinnsformer.ipynb` and `setpinns.ipynb` for the comparison. 

On the exact same problem, with the same seed, model, and setup, PINNsFormer ends up with a trivial solution (with a high error rate) and significantly longer runtime (due to convergence issues), whereas SetPINNs provides a very low error rate.