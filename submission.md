---
layout: default
title: Submission
---

<div class="container">
    <div class="row">
        <div class="col-lg-8 mx-auto">
            <h1 class="text-center mb-5">Submission Guidelines</h1>
            
            <div class="card mb-4">
                <div class="card-body">
                    <h2 class="card-title">Important Dates</h2>
                    <div class="timeline-dates">
                        <div class="timeline-date">
                            <i class="fas fa-calendar-alt"></i>
                            <div>
                                <h4>Paper Submission Deadline</h4>
                                <p>May 9, 2025</p>
                            </div>
                        </div>
                        <div class="timeline-date">
                            <i class="fas fa-envelope"></i>
                            <div>
                                <h4>Notification of Acceptance</h4>
                                <p>June 6, 2025</p>
                            </div>
                        </div>
                        <div class="timeline-date">
                            <i class="fas fa-file-alt"></i>
                            <div>
                                <h4>Camera-ready Submission</h4>
                                <p>June 20, 2025</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card mb-4">
                <div class="card-body">
                    <h2 class="card-title">Submission Types</h2>
                    <div class="submission-types">
                        <div class="submission-type">
                            <i class="fas fa-file-alt"></i>
                            <h3>Full Papers</h3>
                            <p>Original research papers (6-8 pages)</p>
                        </div>
                        <div class="submission-type">
                            <i class="fas fa-lightbulb"></i>
                            <h3>Position Papers</h3>
                            <p>Novel ideas and perspectives (4-6 pages)</p>
                        </div>
                        <div class="submission-type">
                            <i class="fas fa-tasks"></i>
                            <h3>Work-in-Progress</h3>
                            <p>Preliminary results (2-4 pages)</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card mb-4">
                <div class="card-body">
                    <h2 class="card-title">Paper Format</h2>
                    <ul class="format-list">
                        <li>Papers must be submitted in PDF format</li>
                        <li>Use the IJCAI 2025 LaTeX style files</li>
                        <li>Include all figures and references in the page limit</li>
                        <li>Papers must be written in English</li>
                    </ul>
                </div>
            </div>

            <div class="card mb-4">
                <div class="card-body">
                    <h2 class="card-title">Topics of Interest</h2>
                    <div class="topics-list">
                        <div class="topic-section">
                            <h3><i class="fas fa-project-diagram me-2"></i>Causal Inference for Recommender Systems</h3>
                            <ul>
                                <li>Integrating causal models to improve recommendation quality</li>
                                <li>Modeling cause-effect relationships in user behavior and preferences</li>
                                <li>Causal discovery techniques for recommendation system design</li>
                            </ul>
                        </div>

                        <div class="topic-section">
                            <h3><i class="fas fa-balance-scale me-2"></i>Bias and Fairness in Recommendations</h3>
                            <ul>
                                <li>Identifying and mitigating biases in recommender algorithms using causal frameworks</li>
                                <li>Fairness-aware recommendation models based on causal inference</li>
                                <li>Evaluating fairness in recommendation systems using counterfactuals</li>
                            </ul>
                        </div>

                        <div class="topic-section">
                            <h3><i class="fas fa-lightbulb me-2"></i>Interpretability and Transparency</h3>
                            <ul>
                                <li>Explaining recommendations through causal reasoning</li>
                                <li>Causal explanations of user-item interactions</li>
                                <li>Methods for generating interpretable recommendation models</li>
                            </ul>
                        </div>

                        <div class="topic-section">
                            <h3><i class="fas fa-random me-2"></i>Counterfactual Learning and Evaluation</h3>
                            <ul>
                                <li>Applying counterfactual analysis to evaluate recommendation effectiveness</li>
                                <li>Generating personalized counterfactuals for better recommendations</li>
                                <li>Using counterfactuals to measure the impact of recommendation interventions</li>
                            </ul>
                        </div>

                        <div class="topic-section">
                            <h3><i class="fas fa-robot me-2"></i>Causal Reinforcement Learning</h3>
                            <ul>
                                <li>Combining causal inference with reinforcement learning for personalized recommendations</li>
                                <li>Adaptive recommendation strategies based on causal reasoning</li>
                                <li>Dynamic recommendation systems using causal reinforcement learning</li>
                            </ul>
                        </div>

                        <div class="topic-section">
                            <h3><i class="fas fa-industry me-2"></i>Practical Applications and Case Studies</h3>
                            <ul>
                                <li>Real-world applications of causal inference in recommender systems</li>
                                <li>Case studies of deploying causal models in large-scale recommendation systems</li>
                                <li>Lessons learned from industry applications of causal-based recommendation models</li>
                            </ul>
                        </div>

                        <div class="topic-section">
                            <h3><i class="fas fa-shield-alt me-2"></i>Ethical Implications</h3>
                            <ul>
                                <li>Ethical concerns and trade-offs in causal recommendation algorithms</li>
                                <li>Addressing societal impacts and biases in causal recommendation models</li>
                                <li>Incorporating ethical considerations into causal model development</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-body">
                    <h2 class="card-title">Submission Process</h2>
                    <ol class="submission-steps">
                        <li>Prepare your paper following the format guidelines</li>
                        <li>Submit through the workshop's submission system</li>
                        <li>Papers will be reviewed by at least 3 reviewers</li>
                        <li>Authors will receive detailed feedback</li>
                        <li>Accepted papers will be presented at the workshop</li>
                    </ol>
                    <div class="text-center mt-4">
                        <a href="https://easychair.org/conferences/?conf=ijcai2025causalrecsys" class="btn btn-primary">Submit Your Paper</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
.timeline-dates {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
}

.timeline-date {
    display: flex;
    align-items: center;
    gap: 1rem;
}

.timeline-date i {
    font-size: 2rem;
    color: var(--secondary-color);
}

.timeline-date h4 {
    margin: 0;
    color: var(--primary-color);
}

.timeline-date p {
    margin: 0;
    color: #666;
}

.submission-types {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5rem;
    margin-top: 1rem;
}

.submission-type {
    text-align: center;
    padding: 1.5rem;
    background: var(--light-gray);
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.submission-type:hover {
    transform: translateY(-5px);
}

.submission-type i {
    font-size: 2rem;
    color: var(--secondary-color);
    margin-bottom: 1rem;
}

.submission-type h3 {
    font-size: 1.2rem;
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

.format-list {
    list-style: none;
    padding: 0;
}

.format-list li {
    padding: 0.5rem 0;
    padding-left: 2rem;
    position: relative;
}

.format-list li::before {
    content: '•';
    color: var(--secondary-color);
    position: absolute;
    left: 0;
}

.topics-list {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    padding: 1rem 0;
}

.topic-section {
    background: var(--light-gray);
    border-radius: 10px;
    padding: 1.5rem;
    transition: transform 0.3s ease;
}

.topic-section:hover {
    transform: translateY(-5px);
}

.topic-section h3 {
    color: var(--primary-color);
    font-size: 1.3rem;
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
}

.topic-section h3 i {
    color: var(--secondary-color);
}

.topic-section ul {
    list-style: none;
    padding-left: 0;
    margin-bottom: 0;
}

.topic-section ul li {
    position: relative;
    padding-left: 1.5rem;
    margin-bottom: 0.5rem;
    color: var(--text-color);
}

.topic-section ul li:last-child {
    margin-bottom: 0;
}

.topic-section ul li::before {
    content: '•';
    color: var(--secondary-color);
    position: absolute;
    left: 0;
}

.submission-steps {
    padding-left: 1.5rem;
}

.submission-steps li {
    margin-bottom: 1rem;
    color: #666;
}

.submission-steps li:last-child {
    margin-bottom: 0;
}

@media (max-width: 768px) {
    .submission-types {
        grid-template-columns: 1fr;
    }
    
    .topic-section {
        padding: 1rem;
    }
}
</style> 