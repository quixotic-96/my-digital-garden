---
title: Choose your own adventure
layout: page
---

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
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
        }
    </style>
</head>
<body>
    <h1>Topics</h1>
    <div class="grid-container">
        <div class="grid-item">
            <h2>[[Craft]]</h2>
            <p>Fiber arts et al.</p>
        </div>
        <div class="grid-item">
            <h2>[[Theology]]</h2>
            <p>Lord have mercy.</p>
        </div>
        <div class="grid-item">
            <h2>[[Growing]]</h2>
            <p>Plants. Also hopefully myself.</p>
    </div>
	

