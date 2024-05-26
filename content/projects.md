---
title: 'Projects'
url: '/projects'
ShowBreadCrumbs: false
ShowWordCount: false
ShowReadingTime: false
hidemeta: true
showtoc: false
tags: ["Project","Portfolio"]
---


{{< rawhtml >}}

<br/><br/>

<style>
    .card-container {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 20px;
        justify-content: center;
    }
    .card {
        width: 330px;
        height: 560px; /* Fixed height for the card */
        background-color: #fff;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }
    .card img {
        width: 100%;
        display: block;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
        margin-top: 0px;
    }
    .card-content {
        padding: 0px 20px;
    }
    .card-title {
        margin-top: 0;
        margin-bottom: 10px;
        font-size: 20px;
        font-weight: bold;
    }
    .card-description {
        margin-top: 0;
        margin-bottom: 20px;
        font-size: 16px;
    }
    .card-button {
        display: block;
        width: 100%;
        padding: 10px 20px;
        background-color: #1e1e1e;
        color: #fff;
        border: none;
        border-radius: 5px;
        font-size: 16px;
        cursor: pointer;
        text-align: center;
    }

    /* Override Dark mode on Cards */
    .dark .card-title,.card-description, .card-description a{
    color: #000; /* Change to your desired text color */
    }
</style>

<div class="card-container">
    <div class="card">
        <img src="/img/isagani-jaen.png" alt="Image">
        <div class="card-content">
            <h2 class="card-title">Personal Website</h2>
            <p class="card-description">My online portfolio, <a href="https://isaganijaen.com">isaganijaen.com</a> was created using Hugo.</p>
            <a href="/"class="card-button">Visit Site</a>
        </div>
    </div>
    <div class="card">
        <img src="/img/prodAI.png" alt="Image">
        <div class="card-content">
            <h2 class="card-title">ProdAI - AI Personal Assistant</h2>
            <p class="card-description">My AI personal assistant powered by Gemma 2B, Tailwind CSS, DaisyUI and VueJS.</p>
            <a href="https://github.com/isaganijaen/prodai"class="card-button">Visit Repository</a>
        </div>
    </div>    
</div>








{{< /rawhtml >}}