# Workflows Overview

This is an overview of ComfyUI workflows delivered to Pickford for use in the Unity SDK. 

> API Key: 

## SDXL Image

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered image. To run this workflow via Unity SDK, select the workflow named `pickford_sdxl_image`.

## CogVideoX Simple

This workflow takes a prompt and render passes captured from Unity and outputs a rendered video. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_simple`.

## CogVideoX Segmented (1 pass)

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered video using an SDXL reference image. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_segmented_1pass`.

## CogVideoX Segmented (2 passes)

This workflow takes 4 segmented mask prompts, a scene prompt, and render passes captured from Unity and outputs a rendered video using an SDXL reference image and an SDXL vidoe. To run this workflow via Unity SDK, select the workflow named `pickford_cogvideox_segmented_2pass`.
