# Results

The figures below are reported results from the original 2022 Final Year Project. They are retained as historical project results and are not presented as newly reproduced experiments.

## Reported model comparison

The original project report describes the following approximate accuracy results:

| Model | Reported accuracy |
| --- | ---: |
| MobileNetV2 | 96% |
| Fine-tuned MobileNetV2 | 99% |
| VGG16 | 83% |
| InceptionV3 | 90% |

The report also contains a separate comparison table with training and validation values for MobileNetV2, VGG16 and InceptionV3. Some values differ from the narrative summary. Rather than combining those values into a single new claim, this repository keeps the distinction clear and refers readers to the original notebooks and project report for the historical experimental record.

## Interpretation

Within the original project experiments, fine-tuning MobileNetV2 produced the strongest reported accuracy. The other architectures were retained for comparison to examine how different transfer-learning approaches performed on the selected classification task.

## Reproducibility note

These results should not be treated as independently reproduced benchmarks from the current repository state. Reproducing them would require access to the original dataset preparation, environment and experimental settings. The notebooks are provided as the surviving implementation record of the original project work.
