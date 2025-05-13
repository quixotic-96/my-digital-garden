---
title: portfolio
layout: note
---

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .grid-item {
            background-color: #eee6ff;
            border-radius: 5px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        @media (max-width: 600px) {
            .grid-container {
                grid-template-columns: 1fr;
            }
        
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">
            <h2>Knitting</h2>
            <li>[[insomnia socks]]</li>
			<li>[[dogwood blanket]]</li>
			<li>[[penrose tile blanket]]</li>
        </div>
        <div class="grid-item">
            <h2>Sewing</h2>
			<li>[[summer pinwheels]]</li>
            <li>[[black linen and seersucker tie dresses]]</li>
			<li>[[rose garden irish chain]]</li>
        </div>
        <div class="grid-item">
            <h2>Embroidery</h2>
            <li>[[grape vines and pippins]]</li>
			<li>[[pomegranates and rowan]]</li>
			<li>[[butterfly harvest]]</li>
        </div>
        <div class="grid-item">
            <h2>Spinning</h2>
            <li></li>
        </div>
        <div class="grid-item">
            <h2>Florals</h2>
            <li></li>
        </div>
        <!--<div class="grid-item">
            <h2>Item 6</h2>
            <p>This is the content for grid item 6.</p>
        </div>-->
    </div>
</body>