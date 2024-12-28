# Workflows Overview

This is an overview of ComfyUI workflows delivered to Pickford for use in the [Unity SDK.](https://docs.playbook3d.com/api-reference/sdk-libraries/sdk-unity) Reference [walkthrough](https://www.loom.com/share/a6ebc1c21edb475fa94cf54ff1ed8472?sid=7415fe82-1077-4f03-9f6f-20bf50300794) for in depth explanations of workflows.

> API Key: 34da58fe-737d-469d-9162-22a54a5ffbed

## SDXL Image

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered image. To run this workflow via Unity SDK, select the workflow named `pickford_sdxl_image`.

## CogVideoX Simple

This workflow takes a prompt and render passes captured from Unity and outputs a rendered video. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_simple`.

## CogVideoX Segmented (1 pass)

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered video using an SDXL reference image. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_segmented_1pass`.

## CogVideoX Segmented (2 passes)

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered video using an SDXL reference image and an SDXL vidoe. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_segmented_2pass`.
