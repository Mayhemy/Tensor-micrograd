# AlexNet from scratch in Rust

The project started as an implementation of Andrej Karpathy's **Micrograd** - a minimalistic autodifferentiation engine for scalar values written in Rust.<br>
From there, the idea evolved into **Tensor Micrograd**, extending the concept to multidimensional tensors instead of scalars with dynamic computation graphs.<br>
The implementation builds the **AlexNet** architecture (2012) entirely from scratch, including a minimalistic training mechanism and a simple data loader, without using any machine learning, deep learning or BLAS libraries.<br>
It shows how convolution, autodiff, optimization (SGD + momentum + L2) can be implemented in Rust and optimized using parallelization.<br>
The test were written with the assistance from large language models (LLMs).<br><br>

Initially inspired by **Micrograd**, the later direction was influenced by **TinyGrad**, serving as a paragon for simplicity.
