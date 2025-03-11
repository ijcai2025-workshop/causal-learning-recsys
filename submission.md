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

            <div class="card">
                <div class="card-body">
                    <h2 class="card-title">Submission Process</h2>
                    <ul class="submission-steps">
                        <li><i class="fas fa-upload me-2"></i>Submit through the workshop's submission system</li>
                        <li><i class="fas fa-users me-2"></i>Papers will be reviewed by at least 3 reviewers</li>
                        <li><i class="fas fa-comments me-2"></i>Authors will receive detailed feedback</li>
                        <li><i class="fas fa-chalkboard-teacher me-2"></i>Accepted papers will be presented at the workshop</li>
                    </ul>
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

.submission-steps {
    list-style: none;
    padding-left: 0;
}

.submission-steps li {
    margin-bottom: 1rem;
    color: #666;
    display: flex;
    align-items: center;
    padding: 0.5rem 0;
}

.submission-steps li:last-child {
    margin-bottom: 0;
}

.submission-steps li i {
    color: var(--secondary-color);
    font-size: 1.2rem;
    min-width: 1.5rem;
}

@media (max-width: 768px) {
    .topic-section {
        padding: 1rem;
    }
}
</style> 