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
            <div class="topics-grid">
                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-project-diagram"></i>
                        <h3>Causal Inference for Recommender Systems</h3>
                    </div>
                    <ul>
                        <li>Integrating causal models to improve recommendation quality</li>
                        <li>Modeling cause-effect relationships in user behavior</li>
                        <li>Causal discovery techniques for system design</li>
                    </ul>
                </div>

                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-balance-scale"></i>
                        <h3>Bias and Fairness</h3>
                    </div>
                    <ul>
                        <li>Identifying and mitigating biases using causal frameworks</li>
                        <li>Fairness-aware recommendation models</li>
                        <li>Evaluating fairness using counterfactuals</li>
                    </ul>
                </div>

                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-lightbulb"></i>
                        <h3>Interpretability and Transparency</h3>
                    </div>
                    <ul>
                        <li>Explaining recommendations through causal reasoning</li>
                        <li>Causal explanations of user-item interactions</li>
                        <li>Methods for interpretable recommendation models</li>
                    </ul>
                </div>

                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-random"></i>
                        <h3>Counterfactual Learning</h3>
                    </div>
                    <ul>
                        <li>Counterfactual analysis for recommendation effectiveness</li>
                        <li>Generating personalized counterfactuals</li>
                        <li>Measuring intervention impacts</li>
                    </ul>
                </div>

                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-robot"></i>
                        <h3>Causal Reinforcement Learning</h3>
                    </div>
                    <ul>
                        <li>Combining causal inference with reinforcement learning</li>
                        <li>Adaptive recommendation strategies</li>
                        <li>Dynamic recommendation systems</li>
                    </ul>
                </div>

                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-industry"></i>
                        <h3>Practical Applications</h3>
                    </div>
                    <ul>
                        <li>Real-world applications in e-commerce and social media</li>
                        <li>Large-scale deployment case studies</li>
                        <li>Industry lessons and best practices</li>
                    </ul>
                </div>

                <div class="topic-card">
                    <div class="topic-header">
                        <i class="fas fa-shield-alt"></i>
                        <h3>Ethical Implications</h3>
                    </div>
                    <ul>
                        <li>Ethical concerns and trade-offs</li>
                        <li>Addressing societal impacts and biases</li>
                        <li>Incorporating ethical considerations</li>
                    </ul>
                </div>
            </div>
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
    background-attachment: fixed;
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
    background: linear-gradient(
        135deg,
        rgba(44, 62, 80, 0.97) 0%,
        rgba(52, 152, 219, 0.90) 40%,
        rgba(41, 128, 185, 0.80) 100%
    );
    z-index: 1;
}

.hero-content {
    position: relative;
    z-index: 2;
    animation: fadeIn 1.5s ease;
}

.hero-section h1 {
    font-weight: 700;
    margin-bottom: 1rem;
    font-size: 4rem;
    animation: fadeInDown 1s ease;
    background: linear-gradient(120deg, #ffffff 0%, #e3e3e3 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    text-shadow: none;
}

.hero-section h2 {
    font-weight: 300;
    margin-bottom: 2rem;
    font-size: 2.5rem;
    animation: fadeInUp 1s ease 0.2s;
    opacity: 0;
    animation-fill-mode: forwards;
    background: linear-gradient(120deg, #ffffff 0%, #e3e3e3 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    text-shadow: none;
}

.hero-section .location {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
    animation: fadeInUp 1s ease 0.4s;
    opacity: 0;
    animation-fill-mode: forwards;
}

.hero-section .date {
    font-size: 1.5rem;
    margin-bottom: 2rem;
    animation: fadeInUp 1s ease 0.6s;
    opacity: 0;
    animation-fill-mode: forwards;
}

.hero-section .location i {
    margin-right: 0.5rem;
    color: #3498db;
    text-shadow: 0 0 10px rgba(52, 152, 219, 0.5);
}

.btn-hero {
    background: linear-gradient(45deg, #3498db, #2980b9);
    color: white;
    border: none;
    padding: 1rem 2.5rem;
    font-size: 1.2rem;
    font-weight: 600;
    transition: all 0.3s ease;
    animation: fadeInUp 1s ease 0.8s;
    opacity: 0;
    animation-fill-mode: forwards;
    border-radius: 50px;
    box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3);
}

.btn-hero:hover {
    background: linear-gradient(45deg, #2980b9, #3498db);
    color: white;
    transform: translateY(-3px);
    box-shadow: 0 6px 20px rgba(52, 152, 219, 0.4);
}

@media (max-width: 768px) {
    .hero-section {
        min-height: 60vh;
        padding: 4rem 0;
        background-attachment: scroll;
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

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
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

.topics-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 2rem;
}

.topic-card {
    background: var(--light-gray);
    border-radius: 10px;
    padding: 1.5rem;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    border: 1px solid rgba(0,0,0,0.1);
}

.topic-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.topic-header {
    display: flex;
    align-items: center;
    margin-bottom: 1rem;
    gap: 1rem;
}

.topic-header i {
    font-size: 1.5rem;
    color: var(--secondary-color);
}

.topic-header h3 {
    margin: 0;
    font-size: 1.2rem;
    color: var(--primary-color);
}

.topic-card ul {
    list-style: none;
    padding-left: 0;
    margin-bottom: 0;
}

.topic-card ul li {
    position: relative;
    padding-left: 1.5rem;
    margin-bottom: 0.5rem;
    color: var(--text-color);
    font-size: 0.95rem;
}

.topic-card ul li:last-child {
    margin-bottom: 0;
}

.topic-card ul li::before {
    content: '•';
    color: var(--secondary-color);
    position: absolute;
    left: 0;
}

@media (max-width: 768px) {
    .topics-grid {
        grid-template-columns: 1fr;
    }
    
    .topic-card {
        padding: 1rem;
    }
}
</style> 