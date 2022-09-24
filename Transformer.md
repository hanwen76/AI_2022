## Structure
- encoder
  1. embedding & add position information
  2. multi-head attention (based on self-attention) including key\value\query
  3. input every seperate word vector into FFN
  4. sub-layers are connected by residual block
  5. the final result will be put into decoder as key & value
- decoder
  1. self-regression
  2. using masked multi-head attention block can ensure that each output would not generate by vector behind(after) it