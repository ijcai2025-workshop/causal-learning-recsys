---
layout: default
title: Schedule
---

<div class="container">
    <div class="row">
        <div class="col-lg-8 mx-auto">
            <h1 class="text-center mb-5">Workshop Schedule</h1>
            
            <div class="card mb-4">
                <div class="card-body">
                    <h2 class="card-title">Workshop Details</h2>
                    <div class="workshop-details">
                        <p><i class="fas fa-map-marker-alt me-2"></i> Montreal, Canada</p>
                        <p><i class="fas fa-calendar-alt me-2"></i> August 16th – 22nd, 2025</p>
                        <p><i class="fas fa-clock me-2"></i> Full Day Workshop</p>
                        <p><i class="fas fa-university me-2"></i> Venue details will be announced soon</p>
                    </div>
                </div>
            </div>
            
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-flag"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>9:00 AM - 9:15 AM</h3>
                        <h4>Welcome and Opening Remarks</h4>
                        <p>Introduction to the workshop and overview of the day</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>9:15 AM - 10:00 AM</h3>
                        <h4>Invited Keynote 1</h4>
                        <p>First keynote presentation</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-file-alt"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>10:00 AM - 10:45 AM</h3>
                        <h4>Contributed Paper Session 1</h4>
                        <p>Presentations of accepted papers</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-coffee"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>10:45 AM - 11:00 AM</h3>
                        <h4>Coffee Break</h4>
                        <p>Networking and refreshments</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-file-alt"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>11:00 AM - 12:00 PM</h3>
                        <h4>Contributed Paper Session 2</h4>
                        <p>Presentations of accepted papers</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-utensils"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>12:00 PM - 1:00 PM</h3>
                        <h4>Lunch Break</h4>
                        <p>Lunch and networking</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>1:00 PM - 1:45 PM</h3>
                        <h4>Invited Keynote 2</h4>
                        <p>Second keynote presentation</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-users"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>1:45 PM - 2:30 PM</h3>
                        <h4>Poster Session and Networking Break</h4>
                        <p>Interactive poster presentations and discussions</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-comments"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>2:30 PM - 3:15 PM</h3>
                        <h4>Breakout Group Discussion</h4>
                        <p>Small group discussions on key topics</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-file-alt"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>3:15 PM - 4:00 PM</h3>
                        <h4>Contributed Paper Session 3</h4>
                        <p>Presentations of accepted papers</p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-badge">
                        <i class="fas fa-flag-checkered"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>4:00 PM - 4:30 PM</h3>
                        <h4>Closing Remarks</h4>
                        <p>Summary and wrap-up of the workshop</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
.timeline {
    position: relative;
    padding: 2rem 0;
}

.timeline::before {
    content: '';
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    width: 2px;
    height: 100%;
    background: var(--gradient-primary);
}

.timeline-item {
    position: relative;
    margin-bottom: 3rem;
    width: 100%;
}

.timeline-badge {
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background: var(--gradient-primary);
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 1.5rem;
    z-index: 1;
}

.timeline-content {
    width: calc(50% - 50px);
    padding: 1.5rem;
    background: white;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    position: relative;
    transition: transform 0.3s ease;
}

.timeline-content:hover {
    transform: translateY(-5px);
}

.timeline-item:nth-child(odd) .timeline-content {
    margin-left: auto;
}

.timeline-content h3 {
    color: var(--secondary-color);
    font-size: 1.1rem;
    margin-bottom: 0.5rem;
}

.timeline-content h4 {
    color: var(--primary-color);
    font-size: 1.3rem;
    margin-bottom: 0.5rem;
}

@media (max-width: 768px) {
    .timeline::before {
        left: 30px;
    }
    
    .timeline-badge {
        left: 30px;
    }
    
    .timeline-content {
        width: calc(100% - 80px);
        margin-left: 80px !important;
    }
}

.workshop-details {
    margin-top: 1rem;
    padding: 1rem;
    background: var(--light-gray);
    border-radius: 10px;
}

.workshop-details p {
    margin-bottom: 0.5rem;
    color: var(--text-color);
}

.workshop-details i {
    color: var(--secondary-color);
    width: 20px;
}
</style> 