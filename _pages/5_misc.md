---
layout: page
permalink: /misc/
title: misc
nav: true
nav_order: 5
---

<style>
    .flash-container {
        background-color: white; /* White background for the block */
        border-radius: 10px; /* Rounded corners */
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Shadow effect */
        padding: 20px; /* Padding around the content */
        text-align: center; /* Center text inside the block */
        margin-top: 20px; /* Space above the block */
    }

    .flash-card {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 20px 0; /* Space around images */
    }

    .flash-card img {
        border-radius: 50%; /* Keep images round */
        width: 150px; /* Set a fixed size for larger screens */
        height: 150px; /* Ensure height matches width for round shape */
        object-fit: cover;
        margin: 0 10px; /* Space between images */
        transition: transform 0.3s; /* Animation on hover */
    }

    .flash-card img:hover {
        transform: scale(1.05); /* Slightly enlarge on hover */
    }

    .donation-container {
        background-color: white; /* White background for the donation block */
        border-radius: 10px; /* Rounded corners */
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); /* Shadow effect */
        padding: 20px; /* Padding around the content */
        text-align: center; /* Center text inside the block */
        margin-top: 20px; /* Space above the block */
    }

    .donation-list {
        padding: 0; /* Remove padding */
        margin: 20px 0; /* Space above and below */
        display: flex;
        justify-content: center; /* Center the items */
        flex-wrap: wrap; /* Allow items to wrap */
    }

    .donation-list li {
        margin: 0 15px; /* Space between items */
    }

    /* Media query for responsive adjustments */
    @media (max-width: 600px) {
        .flash-card img {
            width: 100px; /* Smaller size for mobile, maintain round shape */
            height: 100px; /* Ensure height matches width for round shape */
        }
        .donation-container, .flash-container {
            padding: 15px; /* Adjust padding for smaller screens */
        }
    }
</style>

<div class="donation-container">
    <div class="donation-comment">
        <p>I donate to the following 501(c)(3) non-profit organizations that support Ukraine:</p>
        <ul class="donation-list">
            <li><a href="https://www.razomforukraine.org/">Razom for Ukraine</a></li>
            <li><a href="https://www.volia.fund/">Volia Fund</a></li>
            <li><a href="https://dignitas.fund/">Dignitas Ukraine</a></li>
        </ul>
    </div>
</div>

<div class="flash-container">
    <div class="flash-card">
        <img
            src="{{ '/assets/img/flash2.jpg' }}"
            class="{% if profile.image_circular %}circular-image{% endif %}"
            alt="Flash 2"
        />
        <img
            src="{{ '/assets/img/flash.jpg' }}"
            class="{% if profile.image_circular %}circular-image{% endif %}"
            alt="Flash"
        />
        <img
            src="{{ '/assets/img/flash3.jpg' }}"
            class="{% if profile.image_circular %}circular-image{% endif %}"
            alt="Flash 3"
        />
    </div>
    <div class="flash-comment">
        <p>If you hear barking during our Zoom calls, don’t be surprised — it's just Flash saying hi and wanting to join the fun!</p>
    </div>
</div>
