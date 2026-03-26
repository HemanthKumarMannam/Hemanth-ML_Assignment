# When Should You Use GRU Instead of LSTM? A Tutorial on Sequence Model Trade-offs

## Overview
This project compares GRU and LSTM on a sequence classification task to study the trade-off between model complexity, training efficiency, and predictive performance.

## Dependencies
Install the required packages with:

```bash
pip install torch numpy matplotlib                                                      How to run
Open the notebook or Python script in your environment.
Run the code from top to bottom.
The code will:
generate the synthetic waveform dataset
train the GRU model
train the LSTM model
print a summary table
generate the figures used in the tutorial
Outputs

Running the code will produce:

example waveform plot
parameter count comparison
validation accuracy plot
final test accuracy plot
average epoch training time plot
summary results table
Main result

Both GRU and LSTM achieved the same final test accuracy on this task, but GRU used fewer parameters. This suggests that GRU was the simpler model without losing predictive performance.

Accessibility

Figures use clear labels, descriptive captions, and readable formatting. Line plots use markers and line styles in addition to colour so that comparisons are not communicated by colour alone.

License

This project can be released under the MIT License.
