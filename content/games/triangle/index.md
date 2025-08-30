+++
date = "2025-08-31T00:00:00+02:00"
draft = false
title = "Wgpu Triangle test"
toc = false
tags = ["rust", "wgpu", "winit"]
categories = ["scratch"]
description = "A triangle. That it"
image = "thumbnail.png"
+++

## About

A simple triangle rendered using WGPU and WebAssembly.

## Play the Game

<div style="width: 100%; height: 600px; border: 2px solid #333; border-radius: 8px; overflow: hidden; margin: 20px 0;">
    <canvas id="wgpu-canvas" style="width: 100%; height: 100%; display: block;"></canvas>
</div>

<script type="module">
    import init from './wgpu_test2.js';
    init();
</script>

<style>
    #wgpu-canvas {
        background: #000;
    }
</style>


