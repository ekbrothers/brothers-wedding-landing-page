---
layout: default
title: Wedding Media
---

<style>
body {
    font-family: Arial, sans-serif;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    text-align: center;
}
.container {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    margin-top: 20px;
}
.qr-code {
    max-width: 300px;
    margin: 20px auto;
}
.video-container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    max-width: 100%;
    margin: 20px 0;
}
.video-container video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
</style>

<div class="container">
    <h1>Welcome to Our Wedding Media Page</h1>
    
    <div class="qr-code">
        <!-- Placeholder for QR code -->
        <img src="qr-code.png" alt="QR Code" style="max-width: 100%; height: auto;">
    </div>

    <div class="video-container">
        <!-- Placeholder for video -->
        <video controls>
            <source src="wedding-video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
