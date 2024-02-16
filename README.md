# OpenSORA
This repo intends to be an open discussion & implementation platform for the technical reproduction of video generative models with quality on par with sora. 

OpenAI sora technical report summary:

1. The overall framework is similar to WALT but with many missing details.
2. The main improvements seem to come from model scaling. 16x compute model shows significantly better spatial & temporal quality
3. The video compression network could be similar to MAGVIT2 but with a higher temporal compression ratio. The number of frames could be very high, as suggested by a previous Google paper.
4. It is probable that casual attention is used for temporal modeling since it supports both image and video data.
5. learning at high resolution could benefit the model performance also.
6. re-captioning is important for text understanding.
