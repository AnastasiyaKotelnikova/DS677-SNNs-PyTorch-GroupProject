### Phase 1: Dataset Preparation & Model Implementation  
**Tasks Completed by Anastasiya Kotelnikova:**

### March 18, 2025
- Created the GitHub repository and set up version control.
- Established the full project folder structure (`data/`, `models/`, `notebooks/`, `src/`, `results/`).
- Configured Git identity and successfully pushed the initial project structure to GitHub.
- Drafted initial `README.md` and `project_report.md` for documentation.

### March 25, 2025
- Uploaded and organized SHD dataset files (`shd_train.h5.gz` and `shd_test.h5.gz`) for SNN training.
- Inspected and accessed the dataset structure using `h5py`.
- Implemented a PyTorch-compatible `Dataset` and `DataLoader` pipeline for handling event-based spiking data.
- Explored and tested different spiking neural network (SNN) architectures using the Norse library.

### March 27, 2025
- Implemented the full `SNNModel` using Norse's `LIFCell` and PyTorch’s sequential layers.
- Converted spike-based input data into dense tensors for SNN processing using `convert_to_spike_tensor`.
- Set up and executed a training loop that ran for **10 epochs**, using batch processing, loss logging, and optimizer updates.
- Verified successful GPU-based training and monitored the loss decreasing across epochs.
- Finalized notebook merging, verified model output, and pushed updated results to GitHub.


### Phase 2: Model Evaluation & Finalization  
**Tasks Completed by Mehrvish Mirza:**

### April 1, 2025
- Continued from Phase 1 with the finalized `SNNModel` built using Norse’s `LIFCell`.
- Initialized the model with input/output configurations and prepared it for GPU execution.
- Set up and executed the training loop for the spiking model, including:
  - Batch iteration with spike conversion.
  - Forward pass, loss computation, and backpropagation.
  - Validation of batch-level performance and logging training loss.
- Trained the model for **3 epochs**, observing reduction in loss and logging results.

### April 5, 2025
- Implemented accuracy evaluation for the trained SNN model using test data.
- Generated predictions by averaging output spikes across time steps.
- Compared predicted vs. actual labels and visualized outcomes.
- Calculated overall classification accuracy and identified incorrect classifications.
- Assessed model output consistency and logged performance observations.

### April 9, 2025
- Completed runtime and performance evaluation of the trained SNN.
- Compared results with expected ANN baselines in terms of accuracy and computational behavior.
- Discussed biological plausibility vs. deep learning trade-offs in SNN performance.
- Reviewed notebook code and final documentation for structure and clarity.
- Verified correct file placement and GitHub project sync.

### April 15, 2025  
- Completed and finalized the written `project_report.md` including:
  - Phase 1 and Phase 2 work summaries
  - Dataset overview
  - Model design, training process, and evaluation results
  - Lessons learned and next steps

- Created and finalized the group PowerPoint presentation covering:
  - Project motivation and goals
  - Overview of Spiking Neural Networks and Norse
  - Dataset details and preprocessing
  - Model architecture and training
  - Key results and evaluation comparisons
  - Reflections and future improvements

- Ensured all project files were properly organized, committed, and pushed to GitHub.
- Reviewed final deliverables for clarity, completeness, and formatting consistency.


