# Workflows Overview

This is an overview of ComfyUI workflows delivered to Pickford for use in the [Unity SDK.](https://docs.playbook3d.com/api-reference/sdk-libraries/sdk-unity)

## SDXL 3D to Image

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered image with SDXL. To run this workflow via Unity SDK, select the workflow named `pickford_sdxl_image`.

## Flux 3D to Image

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered image with Flux. To run this workflow via Unity SDK, select the workflow named `pickford_flux_image`.

## CogVideoX 3D to Video

This workflow takes a prompt and render passes captured from Unity and outputs a rendered video. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_3D2video`.

## CogVideoX 3D to Video Segmented

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered video using an SDXL reference image. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_3D2video_segmented`.

## CogVideoX AnimateDiff 3D to Video Segmented

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered video using an SDXL reference image and SDXL AnimateDiff. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_animatediff_3D2video_segmented`.
