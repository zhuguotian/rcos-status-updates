## Last Week's Accomplishments

So all the parmater from that wavenet papaer has been sorted out and formed as a skeleton for the wavenet model, here is a list of those paramaters:
    # number of the input audio file, usually 1
    batch_size,
    # dilation factors
    dilations,
    # samples that are included after dilating
    filter_width,
    # number of filters to learn for the residual.
    residual_channels,
    # number of filters to learn for the dilation.
    dilation_channels,
    # number of filters to learn that contribute to the quantized softmax output
    skip_channels,
    # 8-bit quantization.
    quantization_channels=2**8,
    # if biased layer exists(set false as default)
    use_biases=False,
    # something from paper, default false
    scalar_input=False,
    # inital layer
    initial_filter_width=32,
    # store histogram or not
    histograms=False
    
## This Week's Plan

Jon is working on the datagenerator and I'll try to implement the loss function for the wavenet model.

## Anything Blocking?

Writing code is hArD

## Notes
