---
layout: default
title: Home
---

<div class="hero-section text-center">
    <div class="hero-overlay"></div>
    <div class="container">
        <div class="hero-content">
            <h1 class="display-3 mb-4">IJCAI 2025 Workshop</h1>
            <h2 class="display-4 mb-4">Causal Learning for Recommendation Systems</h2>
            <p class="location mb-3">
                <i class="fas fa-map-marker-alt"></i>
                Montreal, Canada
            </p>
            <p class="lead date mb-4">August 16th – 22nd, 2025</p>
            <a href="{{ site.baseurl }}/submission" class="btn btn-hero btn-lg">Submit Your Paper</a>
        </div>
    </div>
</div>

<div class="container mt-5">
    <div class="row">
        <div class="col-md-8">
            <h2>About the Workshop</h2>
            <p>
                The IJCAI 2025 Workshop on Causal Learning for Recommendation Systems brings together researchers and practitioners to explore the intersection of causal inference and recommendation systems. This workshop aims to address the challenges and opportunities in incorporating causal reasoning into recommendation algorithms, with a focus on improving recommendation fairness, robustness, and interpretability.
            </p>
            
            <h2 class="mt-4">Key Topics</h2>
            <ul>
                <li>Causal inference in recommendation systems</li>
                <li>Counterfactual learning for recommendations</li>
                <li>Fairness and bias in recommendation systems</li>
                <li>Interpretable recommendation models</li>
                <li>Robust recommendation systems</li>
                <li>Real-world applications and case studies</li>
            </ul>
        </div>
        
        <div class="col-md-4">
            <div class="card">
                <div class="card-body">
                    <h3 class="card-title">Important Dates</h3>
                    <ul class="list-unstyled">
                        <li><strong>Paper Submission:</strong> May 9, 2025</li>
                        <li><strong>Notification:</strong> June 6, 2025</li>
                        <li><strong>Camera Ready:</strong> June 20, 2025</li>
                        <li><strong>Workshop Date:</strong> August 16th – 22nd, 2025</li>
                    </ul>
                </div>
            </div>
            
            <div class="card mt-4">
                <div class="card-body">
                    <h3 class="card-title">Quick Links</h3>
                    <ul class="list-unstyled">
                        <li><a href="{{ site.baseurl }}/submission">Submission Guidelines</a></li>
                        <li><a href="{{ site.baseurl }}/schedule">Workshop Schedule</a></li>
                        <li><a href="{{ site.baseurl }}/speakers">Invited Speakers</a></li>
                        <li><a href="{{ site.baseurl }}/organizers">Organizers</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="container mt-5">
    <div class="row">
        <div class="col-12">
            <h2 class="text-center">Call for Papers</h2>
            <p class="text-center">
                We invite submissions of original research papers that address theoretical and practical aspects of causal learning in recommendation systems. Both full papers and position papers are welcome.
            </p>
            <div class="text-center mt-4">
                <a href="{{ site.baseurl }}/submission" class="btn btn-primary">Submission Guidelines</a>
            </div>
        </div>
    </div>
</div>

<style>
.hero-section {
    position: relative;
    min-height: 80vh;
    display: flex;
    align-items: center;
    color: white;
    background: url('{{ site.baseurl }}/assets/images/montreal-hero.jpg') no-repeat center center;
    background-size: cover;
    padding: 6rem 0;
    margin-bottom: 3rem;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
}

.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.7));
    z-index: 1;
}

.hero-content {
    position: relative;
    z-index: 2;
}

.hero-section h1 {
    font-weight: 700;
    margin-bottom: 1rem;
    font-size: 4rem;
    animation: fadeInDown 1s ease;
}

.hero-section h2 {
    font-weight: 300;
    margin-bottom: 2rem;
    font-size: 2.5rem;
    animation: fadeInUp 1s ease 0.2s;
}

.hero-section .location {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
    animation: fadeInUp 1s ease 0.4s;
}

.hero-section .date {
    font-size: 1.5rem;
    margin-bottom: 2rem;
    animation: fadeInUp 1s ease 0.6s;
}

.hero-section .location i {
    margin-right: 0.5rem;
    color: var(--secondary-color);
}

.btn-hero {
    background: var(--secondary-color);
    color: white;
    border: 2px solid var(--secondary-color);
    padding: 1rem 2.5rem;
    font-size: 1.2rem;
    font-weight: 600;
    transition: all 0.3s ease;
    animation: fadeInUp 1s ease 0.8s;
}

.btn-hero:hover {
    background: transparent;
    color: white;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

@media (max-width: 768px) {
    .hero-section {
        min-height: 60vh;
        padding: 4rem 0;
    }
    
    .hero-section h1 {
        font-size: 2.5rem;
    }
    
    .hero-section h2 {
        font-size: 1.8rem;
    }
    
    .hero-section .location,
    .hero-section .date {
        font-size: 1.2rem;
    }
}

@keyframes fadeInDown {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
</style> 