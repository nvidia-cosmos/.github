# NVIDIA Cosmos

[NVIDIA Cosmos™](https://www.nvidia.com/en-us/ai/cosmos/) is a platform purpose-built for physical AI, featuring state-of-the-art generative world foundation models (WFMs), robust guardrails, and an accelerated data processing and curation pipeline. Designed specifically for real-world systems, Cosmos enables developers to rapidly advance physical AI applications such as autonomous vehicles (AVs), robots, and video analytics AI agents.

Cosmos World Foundation Models come in three model types which can all be customized in post-training: [cosmos-predict](https://github.com/nvidia-cosmos/cosmos-predict2.5), [cosmos-transfer](https://github.com/nvidia-cosmos/cosmos-transfer2.5), and [cosmos-reason](https://github.com/nvidia-cosmos/cosmos-reason2):

<table align="center">
  <tr>
    <th></th>
    <th><center><a href="https://github.com/nvidia-cosmos/cosmos-predict2.5">Predict</a></center></th>
    <th><center><a href="https://github.com/nvidia-cosmos/cosmos-transfer2.5">Transfer</a></center></th>
    <th><center><a href="https://github.com/nvidia-cosmos/cosmos-reason2">Reason</a></center></th>
  </tr>
  <tr>
    <td align="center"><b>Type</b></td>
    <td align="center">World Generation</td>
    <td align="center">Multi-Controlnet</td>
    <td align="center">Reasoning VLM</td>
  </tr>
  <tr>
    <td align="center"><b>Function</b></td>
    <td align="center">Predict novel future frames given initial frames</td>
    <td align="center">Transfer existing control frames into photoreal frames within a video clip</td>
    <td align="center">Reason against frames within a video clip</td>
  </tr>
  <tr>
    <td align="center"><b>Use Cases</b></td>
    <td align="center">Data Generation &amp; Policy Evaluation</td>
    <td align="center">Data Augmentation</td>
    <td align="center">Data Curation, Robot Planning and Policy &amp; Vision AI Agents</td>
  </tr>
  <tr>
    <td align="center"><b>Inputs</b></td>
    <td align="center">Text, Image, Video</td>
    <td align="center">Multiple Video Modalities such as RGB, Depth, Segmentation, and more.</td>
    <td align="center">Video, Image &amp; Text</td>
  </tr>
  <tr>
    <td align="center"><b>Outputs</b></td>
    <td align="center">Video</td>
    <td align="center">Video</td>
    <td align="center">Text</td>
  </tr>
</table>

# NVIDIA Cosmos Cookbook
The [Cosmos Cookbook](https://github.com/nvidia-cosmos/cosmos-cookbook) offers developers step-by-step recipes and post-training scripts to quickly build, customize, and deploy NVIDIA’s Cosmos world foundation models for robotics and autonomous systems.

# Use Cases in Physical AI Development

Our world foundation models are purpose-built to accelerate improving performance in downstream model tasks in various stages, as illustrated here in the flywheel.

![Cosmos Data Flywheel](./DataFlywheel-Sept.jpg)
