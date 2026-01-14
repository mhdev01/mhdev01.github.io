---
layout: default
title: Home - Mani Raghavan
---

<section class="hero">
  <h1 class="hero-title">Senior Software Architect & SaaS Product Builder</h1>
  <p class="hero-subtitle">30+ years of experience designing enterprise-grade systems that scale</p>
  <div class="hero-cta">
    <a href="{{ '/projects.html' | relative_url }}" class="btn btn-primary">View My Projects</a>
    <a href="{{ '/consulting.html' | relative_url }}" class="btn btn-secondary">Let's Collaborate</a>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">What I Do</h2>
      <p class="section-subtitle">Building production-grade platforms and enterprise applications with a focus on scalability, security, and modern architecture</p>
    </div>
    
    <div class="card-grid">
      <div class="card">
        <div class="card-icon">
          <i class="fas fa-building"></i>
        </div>
        <h3>ERP Architecture</h3>
        <p>Multi-tenant SaaS systems with robust audit trails, compliance-ready data models, and enterprise-level security.</p>
      </div>
      
      <div class="card">
        <div class="card-icon">
          <i class="fas fa-cloud"></i>
        </div>
        <h3>Cloud-Native SaaS</h3>
        <p>Production-grade SaaS platforms designed for scalability, with microservices architecture and modern DevOps practices.</p>
      </div>
      
      <div class="card">
        <div class="card-icon">
          <i class="fas fa-robot"></i>
        </div>
        <h3>AI-Powered Automation</h3>
        <p>Business automation using AI agents, LLM integration, and RPA workflows for enterprise process optimization.</p>
      </div>
      
      <div class="card">
        <div class="card-icon">
          <i class="fas fa-puzzle-piece"></i>
        </div>
        <h3>ERP | GRC | Analytics Integration</h3>
        <p>Oracle JDE/EBS and SAP integrations with pgvector analytics, governance, SOD analysis, audit reporting, and JML access workflows.</p>
      </div>
    </div>
  </div>
</section>

<section class="section" style="background: var(--color-bg-secondary); margin: 0 -100vw; padding-left: 100vw; padding-right: 100vw;">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Core Expertise</h2>
    </div>
    
    <div class="card-grid">
      <div class="card">
        <h3><i class="fas fa-server"></i> Backend</h3>
        <ul class="feature-list">
          <li>Python, Django, FastAPI, REST APIs</li>
          <li>RBAC, Audit Trails, Compliance</li>
          <li>Supabase, PostgreSQL (multi-tenant)</li>
        </ul>
      </div>
      
      <div class="card">
        <h3><i class="fas fa-desktop"></i> Frontend</h3>
        <ul class="feature-list">
          <li>React.js, Next.js</li>
          <li>Role-based dashboards</li>
          <li>Enterprise UI workflows</li>
        </ul>
      </div>
      
      <div class="card">
        <h3><i class="fas fa-mobile-alt"></i> Mobile</h3>
        <ul class="feature-list">
          <li>Flutter, React Native</li>
          <li>Role-based access</li>
          <li>Granular permissions</li>
        </ul>
      </div>
      
      <div class="card">
        <h3><i class="fas fa-puzzle-piece"></i> ERP | GRC | Analytics</h3>
        <ul class="feature-list">
          <li>Oracle JDE/EBS (pgvector, Analytics, real-time reporting)</li>
          <li>SAP (Governance, SOD, Audit reports, JML workflows)</li>
          <li>AI agents for ERP workflows</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="section-header">
      <h2 class="section-title">Featured Projects</h2>
      <p class="section-subtitle">Production-grade systems serving real businesses and governments</p>
    </div>
    
    <div class="card-grid">
      <div class="project-card">
        <img src="{{ '/assets/images/project-vehicle.png' | relative_url }}" alt="Government Vehicle Testing System" class="project-image">
        <div class="project-content">
          <h3>Government Vehicle Testing & Certification</h3>
          <p class="project-description">End-to-end certification workflow with IoT, testing equipment, Ministry of Transport, payment gateway, and SMS/email integrations for a government organization.</p>
          <div class="tech-badges">
            <span class="badge">React</span>
            <span class="badge">Django</span>
            <span class="badge">PostgreSQL</span>
            <span class="badge">AWS</span>
            <span class="badge">IoT</span>
          </div>
          <a href="{{ '/projects.html#vehicle-testing' | relative_url }}" class="btn btn-secondary">Learn More</a>
        </div>
      </div>
      
      <div class="project-card">
        <img src="{{ '/assets/images/project-erp.png' | relative_url }}" alt="Modular ERP SaaS Platform" class="project-image">
        <div class="project-content">
          <h3>Modular ERP SaaS Platform</h3>
          <p class="project-description">Multi-tenant SaaS with CRM, Sales, HRMS, and WhatsApp/social media integration. RAG/AI agents for sales and support automation.</p>
          <div class="tech-badges">
            <span class="badge">React</span>
            <span class="badge">Django</span>
            <span class="badge">Supabase</span>
            <span class="badge">AI Integration</span>
            <span class="badge">WhatsApp API</span>
          </div>
          <a href="{{ '/projects.html#erp-platform' | relative_url }}" class="btn btn-secondary">Learn More</a>
        </div>
      </div>
      
      <div class="project-card">
        <img src="{{ '/assets/images/project-ai.png' | relative_url }}" alt="AI Business Automation" class="project-image">
        <div class="project-content">
          <h3>AI-Ready Business Automation</h3>
          <p class="project-description">LLM-based AI agents for ERP/CRM workflows with RPA nodes (OCR, email, notifications), AI report generator, and Temporal workflow engine.</p>
          <div class="tech-badges">
            <span class="badge">Python</span>
            <span class="badge">LLM</span>
            <span class="badge">Temporal</span>
            <span class="badge">RPA</span>
            <span class="badge">OCR</span>
          </div>
          <a href="{{ '/projects.html#ai-automation' | relative_url }}" class="btn btn-secondary">Learn More</a>
        </div>
      </div>
    </div>
    
    <div style="text-align: center; margin-top: var(--spacing-2xl);">
      <a href="{{ '/projects.html' | relative_url }}" class="btn btn-primary">View All Projects</a>
    </div>
  </div>
</section>

<section class="section" style="background: var(--color-bg-secondary); margin: 0 -100vw; padding-left: 100vw; padding-right: 100vw;">
  <div class="container">
    <div class="highlight-box">
      <p style="font-size: var(--font-size-lg); font-style: italic; text-align: center;">
        "I focus on designing scalable SaaS platforms, ERP systems, and AI-assisted business automation that hold up in real production environments."
      </p>
    </div>
    
    <div style="text-align: center; margin-top: var(--spacing-2xl);">
      <h3>Ready to collaborate?</h3>
      <div style="display: flex; gap: var(--spacing-md); justify-content: center; margin-top: var(--spacing-lg); flex-wrap: wrap;">
        <a href="mailto:{{ site.author.email }}" class="btn btn-primary">
          <i class="fas fa-envelope"></i> Email Me
        </a>
        <a href="{{ site.author.linkedin }}" target="_blank" class="btn btn-secondary">
          <i class="fab fa-linkedin"></i> Connect on LinkedIn
        </a>
        <a href="{{ '/resume.pdf' | relative_url }}" target="_blank" class="btn btn-secondary">
          <i class="fas fa-file-pdf"></i> Download Resume
        </a>
      </div>
    </div>
  </div>
</section>
