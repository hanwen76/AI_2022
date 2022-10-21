## basic idea
- an image is worth 16*16 words(patches)
- turn 2D image to 1D serie
- every single patch can be connected and joined together as a linear embedding
## model description
- patches -> linear projection -> features (patch embedding) & position embedding -> token
- token -> self-attention -> ...