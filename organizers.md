---
layout: default
title: Organizers
---

<div class="container">
    <div class="row">
        <div class="col-12">
            <h1 class="text-center mb-5">Workshop Organizers</h1>
            <p class="text-center lead mb-5">The organizing committee will be announced soon.</p>
        </div>
    </div>

    <div class="row">
        <div class="col-12">
            <div class="alert alert-info text-center">
                <i class="fas fa-info-circle me-2"></i>
                Stay tuned for information about our workshop organizers.
            </div>
        </div>
    </div>
</div>

<style>
.organizer-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
    height: 100%;
}

.organizer-card:hover {
    transform: translateY(-10px);
}

.organizer-image {
    position: relative;
    padding-top: 100%;
    overflow: hidden;
}

.organizer-image img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.organizer-card:hover .organizer-image img {
    transform: scale(1.1);
}

.organizer-content {
    padding: 1.5rem;
}

.organizer-content h3 {
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

.organizer-title {
    color: var(--secondary-color);
    font-weight: 600;
    margin-bottom: 0.25rem;
}

.organizer-affiliation {
    color: var(--text-color);
    font-size: 0.9rem;
    margin-bottom: 1rem;
}

.organizer-bio {
    color: #666;
    font-size: 0.95rem;
    margin-bottom: 1rem;
}

.organizer-social a {
    color: var(--primary-color);
    font-size: 1.2rem;
    transition: color 0.3s ease;
}

.organizer-social a:hover {
    color: var(--secondary-color);
}

@media (max-width: 768px) {
    .organizer-card {
        margin-bottom: 2rem;
    }
}
</style> 