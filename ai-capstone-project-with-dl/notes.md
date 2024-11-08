# Notes from the coursework
## PyTorch
### `torch.LongTensor`
Holds 64-bit signed integers (torch.int64).
In deep learning tasks, `LongTensors` are often used to store:

- Class labels in classification tasks; the 
ground truth labels are often stored as LongTensors.
- Indices for embeddings in NLP models

### `torchvision.transforms`
Use pre-build transform modules for images like:
- `torchvision.transforms.ToTensor`: converts PIL images into
tensors with 3D tensors (in case of RGB).
- `torchvision.transforms.Normalize`: normalizes the tensor
using specified mean and standard deviation.