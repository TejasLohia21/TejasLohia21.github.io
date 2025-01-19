---
permalink: /markdown/
title: "Astrophotography"
author_profile: false
layout: single
classes: wide
redirect_from:
  - /md/
  - /markdown.html
---

<style>
/* Masthead (navigation bar) modifications */
.masthead {
    background-color: #000000 !important;
    border-bottom: 1px solid rgba(255, 255, 255, 0.1) !important;
}

.masthead__inner-wrap {
    background-color: #000000 !important;
}

.greedy-nav {
    background-color: #000000 !important;
}

.greedy-nav a {
    color: #ffffff !important;
}

.greedy-nav .visible-links a:before {
    background: #ffffff !important;
}

.greedy-nav .visible-links a:hover {
    color: #cccccc !important;
}
</style>

<style>
/* Reset layout styles */
.page__content {
    padding: 0 !important;
    margin: 0 !important;
    max-width: none !important;
    float: none !important;
    width: 100vw !important;
    margin-left: calc(-50vw + 50%) !important;
    margin-right: calc(-50vw + 50%) !important;
    background-color: #000000;
}

.page__inner-wrap {
    max-width: none !important;
    padding: 0 !important;
}

.page__title {
    display: none;
}

/* Hide breadcrumbs and other navigation */
.breadcrumbs {
    display: none !important;
}

/* Full screen hero section */
.hero-section {
    height: 100vh;
    width: 100%;
    position: relative;
    background-image: url('/assets/images/astrophotography-background.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
}

.explore-button {
    color: white;
    font-size: 2.5rem;
    text-transform: uppercase;
    letter-spacing: 0.3em;
    text-decoration: none;
    padding: 20px 40px;
    border: 2px solid white;
    transition: all 0.3s ease;
    background-color: rgba(0, 0, 0, 0.3);
    cursor: pointer;
}

.explore-button:hover {
    background-color: rgba(255, 255, 255, 0.1);
    transform: scale(1.05);
}

.content-section {
    opacity: 0;
    transition: opacity 1s ease;
    background-color: #000000;
    padding: 4rem 2rem;
    min-height: 100vh;
}

.content-section.visible {
    opacity: 1;
}

.astro-content {
    max-width: 1200px;
    margin: 0 auto;
    color: #ffffff;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Ensures two items per row */
    gap: 20px;
    margin-top: 40px;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    transition: transform 0.3s ease;
    background-color: #000000;
}

.gallery-item:hover {
    transform: scale(1.02);
}

.gallery-item img {
    width: 100%; /* Adjusted to take full space */
    max-width: 500px; /* Optional: Set a maximum width */
    height: auto;
    display: block;
    margin: 0 auto; /* Centers the image */
}

.gallery-item-caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.9);
    color: white;
    padding: 10px;
    transform: translateY(100%);
    transition: transform 0.3s ease;
}

.gallery-item:hover .gallery-item-caption {
    transform: translateY(0);
}

/* Hide unnecessary elements */
.page__meta {
    display: none;
}

.page__footer {
    margin-top: 0;
}
</style>

<div class="hero-section">
    <a href="#content" class="explore-button">Explore</a>
</div>

<div id="content" class="content-section">
    <div class="astro-content">
        <h2>Astrophotography</h2>
        <p>Explore my finest astrophotography works..</p>
        <p> - Following are shot from the Unistellar's Evscope 2 of the Astronomy club at IIT Gandhinagar.</p>
        <div class="gallery-grid">
            <div class="gallery-item">
                <img src="/assets/images/Andromeda.png" alt="Andromeda Galaxy">
                <div class="gallery-item-caption">
                    <h3>Andromeda Galaxy</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <!-- Second Image -->
            <div class="gallery-item">
                <img src="/assets/images/Triffid.jpeg" alt="Triffid Nebula">
                <div class="gallery-item-caption">
                    <h3>Triffid Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <!-- Third Image -->
            <div class="gallery-item">
                <img src="/assets/images/Lagoon.jpeg" alt="Lagoon Nebula">
                <div class="gallery-item-caption">
                    <h3>Lagoon Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Pinwheel.png" alt="Pinwheel Nebula">
                <div class="gallery-item-caption">
                    <h3>Pinwheel Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/NGC5128.png" alt="NGC Nebula">
                <div class="gallery-item-caption">
                    <h3>NGC 5128 Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Whirlpool.png" alt="Whirlpool Galaxy">
                <div class="gallery-item-caption">
                    <h3>Whirlpool Galaxy</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Smoke Ring.png" alt="Smoke Ring">
                <div class="gallery-item-caption">
                    <h3>Smoke Ring</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Running_man.png" alt="Running Man Nebula">
                <div class="gallery-item-caption">
                    <h3>Running Man Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Orion.jpeg" alt="Orion Nebula">
                <div class="gallery-item-caption">
                    <h3>Orion Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            
            <div class="gallery-item">
                <img src="/assets/images/Eagle's Nebula.jpeg" alt="Eagle Galaxy">
                <div class="gallery-item-caption">
                    <h3>Eagle's Nebula / Pillars of Creation</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Flame Nebula.jpeg" alt="Flame Nebula">
                <div class="gallery-item-caption">
                    <h3>Flame Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Triangulum.jpeg" alt="Triangulum Galaxy">
                <div class="gallery-item-caption">
                    <h3>Triangulum Galaxy</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Horse Nebula.jpeg" alt="Horse Head Nebula">
                <div class="gallery-item-caption">
                    <h3>Horse head Nebula</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>


            <div class="gallery-item">
                <img src="/assets/images/Mars.jpeg" alt="Mars">
                <div class="gallery-item-caption">
                    <h3>Mars</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Saturn.jpeg" alt="Saturn">
                <div class="gallery-item-caption">
                    <h3>Saturn</h3>
                    <p>Captured with Unistellar's Evscope 2</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Jupiter.jpeg" alt="Jupiter">
                <div class="gallery-item-caption">
                    <h3>Jupiter</h3>
                    <p>Captured with OnePlus 11R using Celestron SkyMaster</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/final.jpeg" alt="Star Trail_1">
                <div class="gallery-item-caption">
                    <h3>Star Trails</h3>
                    <p>Captured with Nikon_Z50</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/final2.jpeg" alt="Star Trail_1">
                <div class="gallery-item-caption">
                    <h3>Star Trails</h3>
                    <p>Captured with Nikon_Z50</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/final3.jpg" alt="Star Trail_1">
                <div class="gallery-item-caption">
                    <h3>Star Trails</h3>
                    <p>Captured with Nikon_Z50</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Milky_Way.jpeg" alt="Milky Way">
                <div class="gallery-item-caption">
                    <h3>Milky Way</h3>
                    <p>Captured with OnePlus 11R</p>
                </div>
            </div>

            


            

            <div class="gallery-item">
                <img src="/assets/images/Wideangle.jpeg" alt="Rand">
                <div class="gallery-item-caption">
                    <h3>Wide Angle Shot</h3>
                    <p>Captured with OnePlus 11R</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/Random.jpeg" alt="Orion Nebula-B">
                <div class="gallery-item-caption">
                    <h3>Wide Angle Capture</h3>
                    <p>Captured with OnePlus 11R</p>
                </div>
            </div>

            <div class="gallery-item">
                <img src="/assets/images/OrionB.jpeg" alt="Orion Nebula-B">
                <div class="gallery-item-caption">
                    <h3>Orion Nebula</h3>
                    <p>Captured with OnePlus 11R using Celestron SkyMaster</p>
                </div>
            </div>

           

            <div class="gallery-item">
                <img src="/assets/images/Moon.jpeg" alt="Moon">
                <div class="gallery-item-caption">
                    <h3>Moon</h3>
                    <p>Captured with OnePlus 11R using Celestron SkyMaster</p>
                </div>
            </div>


        </div>
    </div>
</div>

<script>
document.querySelector('.explore-button').addEventListener('click', function(e) {
    e.preventDefault();
    document.querySelector('#content').scrollIntoView({
        behavior: 'smooth'
    });
});

const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('visible');
        }
    });
});

observer.observe(document.querySelector('.content-section'));
</script>