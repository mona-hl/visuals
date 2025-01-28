gantt
    dateFormat  YYYY-MM-DD
    title       Big Multi-Year Project Plan

    %% Specify the timescale you want to view (by day, week, month, etc.)
    %% Here, we're working quarter by quarter (roughly each quarter ~ 90 days).
    %% Adjust the start date and durations to match your actual plan.

    section Phase 1: Conceptualization
    Research & Discovery        :a1, 2025-01-01, 90d
    Requirements Gathering      :a2, after a1, 60d
    Feasibility Analysis        :a3, after a2, 30d

    section Phase 2: Planning
    Strategic Planning          :b1, after a3, 2025-07-01, 60d
    Resource Allocation         :b2, after b1, 30d
    Detailed Work Breakdown     :b3, after b2, 60d

    section Phase 3: Development
    Core Functionality          :c1, 2025-10-01, 180d
    Beta Testing & Feedback     :c2, after c1, 30d
    Iterative Refinements       :c3, after c2, 60d

    section Phase 4: Implementation
    Infrastructure Setup        :d1, 2026-07-01, 90d
    Final Integration           :d2, after d1, 90d
    System Testing              :d3, after d2, 60d

    section Phase 5: Rollout & Maintenance
    Deployment & Launch         :e1, 2027-01-01, 30d
    Post-launch Monitoring      :e2, after e1, 60d
    Ongoing Maintenance & Ops   :e3, after e2, 180d
