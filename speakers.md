---
layout: default
title: Speakers
---

<div class="container">
    <div class="row">
        <div class="col-12">
            <h1 class="text-center mb-5">Invited Speakers</h1>
            <p class="text-center lead mb-5">Our distinguished speakers will be announced soon.</p>
        </div>
    </div>

    <div class="row">
        <div class="col-12">
            <div class="alert alert-info text-center">
                <i class="fas fa-info-circle me-2"></i>
                Stay tuned for updates about our keynote speakers and panelists.
            </div>
        </div>
    </div>
</div>

<style>
.speaker-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
    height: 100%;
}

.speaker-card:hover {
    transform: translateY(-10px);
}

.speaker-image {
    position: relative;
    padding-top: 100%;
    overflow: hidden;
}

.speaker-image img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.speaker-card:hover .speaker-image img {
    transform: scale(1.1);
}

.speaker-content {
    padding: 1.5rem;
}

.speaker-content h3 {
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

.speaker-title {
    color: var(--secondary-color);
    font-weight: 600;
    margin-bottom: 0.25rem;
}

.speaker-affiliation {
    color: var(--text-color);
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.speaker-bio {
    color: #666;
    font-size: 0.95rem;
    margin-bottom: 1rem;
}

.speaker-social a {
    color: var(--primary-color);
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

.speaker-social a:hover {
    color: var(--secondary-color);
}

.panelist .speaker-content {
    padding: 1rem;
}

.panelist .speaker-bio {
    margin-bottom: 0;
}

@media (max-width: 768px) {
    .speaker-card {
        margin-bottom: 2rem;
    }
}
</style> 