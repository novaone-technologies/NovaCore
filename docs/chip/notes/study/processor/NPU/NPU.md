# NPU - Study

Neural Processing Unit: Which is also known as a AI accelerator - Deep Learning Processor.

It's a designed to accelerate artificial intelligence (AI) and machine learning applications, including artificial neural networks and computer vision.

Source: https://en.wikipedia.org/wiki/Neural_processing_unit

They can and are used to train and use already trained AI models, The most typical applications include algorthms and robotics.

-- a typical AI integrated circuit chip contains tens of billions of MOSFETs.

-- NPUs are optimized for the massively parallel computations required in AI workloads.

| Processor | Strength                                          | Use Case                                  |
| --------- | ------------------------------------------------- | ----------------------------------------- |
| **CPU**   | General-purpose, good at sequential logic         | Operating systems, apps                   |
| **GPU**   | Parallel processing for graphics, adaptable to ML | Training deep learning models             |
| **NPU**   | Dedicated hardware for neural networks            | Running AI models quickly and efficiently |

Architecture:
    Designed around tensor operations (e.g., matrix multiplications).
   - Often includes:

        - High-throughput memory paths

        - Dedicated activation function units

        - Quantization-aware components (for using INT8/FP16 data)

- Lower power consumption compared to GPUs
- Faster inference times for AI tasks
- Offloads AI processing from CPU/GPU