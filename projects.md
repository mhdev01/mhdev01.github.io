---
layout: default
title: Projects - Mani Raghavan
---

<section class="hero" style="padding: var(--spacing-3xl) 0;">
  <h1 class="hero-title">Projects</h1>
  <p class="hero-subtitle">Production-grade systems serving real businesses and government organizations</p>
</section>

<section class="section">
  <div class="container">
    <div id="vehicle-testing" class="project-card" style="margin-bottom: var(--spacing-3xl);">
      <img src="{{ '/assets/images/project-vehicle.png' | relative_url }}" alt="Government Vehicle Testing System" class="project-image">
      <div class="project-content">
        <h2 class="project-title">🏛 Government Vehicle Testing & Certification System</h2>
        <p class="project-description">A comprehensive end-to-end certification workflow system deployed for a government organization, handling vehicle inspections with IoT testing equipment integrations, Ministry of Transport integration, payment gateway, and automated SMS/email notifications.</p>
        
        <h3>Key Features</h3>
        <ul class="feature-list">
          <li>Secure role-based access control (RBAC) for inspectors, administrators, and auditors</li>
          <li>Integration with IoT testing equipment for real-time data capture</li>
          <li>Ministry of Transport integration for regulatory compliance</li>
          <li>Payment gateway integration for fee processing</li>
          <li>Comprehensive audit trails for all certification activities</li>
          <li>Multi-stage approval workflows with digital signatures</li>
        </ul>
        
        <div class="tech-badges">
          <span class="badge">React</span>
          <span class="badge">Django</span>
          <span class="badge">PostgreSQL</span>
          <span class="badge">AWS</span>
          <span class="badge">IoT Integration</span>
          <span class="badge">Payment Gateway</span>
        </div>
        
        <div class="highlight-box mt-2">
          <p><strong>Status:</strong> Production deployment serving a government organization</p>
          <p><strong>Documentation:</strong> Architecture diagrams, ERD, and workflow diagrams available</p>
        </div>
      </div>
    </div>
    
    <div id="erp-platform" class="project-card" style="margin-bottom: var(--spacing-3xl);">
      <img src="{{ '/assets/images/project-erp.png' | relative_url }}" alt="Modular ERP SaaS Platform" class="project-image">
      <div class="project-content">
        <h2 class="project-title">🧩 Modular ERP SaaS Platform</h2>
        <p class="project-description">A comprehensive multi-tenant SaaS platform with integrated CRM, Sales, POS, Purchase, Inventory, Accounts, and HRMS modules. Features WhatsApp, email, and social media integration with RAG/AI agents for sales and support automation.</p>
        
        <h3>Modules & Features</h3>
        <ul class="feature-list">
          <li><strong>CRM & Sales:</strong> Lead management, opportunity tracking, sales pipeline with AI-powered insights</li>
          <li><strong>Point of Sale:</strong> Multi-location POS with inventory sync and real-time reporting</li>
          <li><strong>Purchase & Inventory:</strong> Multi-warehouse management, automated reorder points, vendor management</li>
          <li><strong>Accounts:</strong> Multi-currency support, regional tax compliance, financial reporting</li>
          <li><strong>HRMS & Payroll:</strong> Employee management, attendance tracking, payroll processing</li>
          <li><strong>AI Integration:</strong> WhatsApp bot for customer support, RAG/LLM agents for sales assistance</li>
        </ul>
        
        <h3>Architecture Highlights</h3>
        <ul class="feature-list">
          <li>Multi-tenant SaaS architecture with data isolation at the database level</li>
          <li>Partner & reseller portals with white-label capabilities</li>
          <li>Designed for regional tax & compliance extensions (VAT, GST, etc.)</li>
          <li>REST API for third-party integrations</li>
          <li>Role-based dashboards for different user types</li>
        </ul>
        
        <div class="tech-badges">
          <span class="badge">React</span>
          <span class="badge">Next.js</span>
          <span class="badge">Django Admin</span>
          <span class="badge">Supabase</span>
          <span class="badge">PostgreSQL</span>
          <span class="badge">WhatsApp API</span>
          <span class="badge">AI/LLM</span>
        </div>
        
        <div class="highlight-box mt-2">
          <p><strong>Status:</strong> Active development, beta deployment</p>
          <p><strong>Repository:</strong> Private (enterprise client)</p>
        </div>
      </div>
    </div>
    
    <div id="ai-automation" class="project-card" style="margin-bottom: var(--spacing-3xl);">
      <img src="{{ '/assets/images/project-ai.png' | relative_url }}" alt="AI Business Automation" class="project-image">
      <div class="project-content">
        <h2 class="project-title">🤖 AI-Ready Business Automation</h2>
        <p class="project-description">Advanced AI agent system for automating complex ERP/CRM workflows using LLM-based reasoning with RPA nodes for trigger-based actions (OCR, email, push notifications), AI report generator chatbot, and Temporal workflow engine for complex orchestration.</p>
        
        <h3>Capabilities</h3>
        <ul class="feature-list">
          <li><strong>LLM-Based AI Agents:</strong> Natural language processing for ERP workflow automation</li>
          <li><strong>AI Report Generator:</strong> Automated business intelligence reports with natural language summaries</li>
          <li><strong>RPA Nodes:</strong> Robotic process automation for non-AI interface integration</li>
          <li><strong>Temporal Workflows:</strong> Reliable orchestration of long-running business processes</li>
          <li><strong>Third-Party Integrations:</strong> Seamless connection with external systems and APIs</li>
        </ul>
        
        <h3>Use Cases</h3>
        <ul class="feature-list">
          <li>Lead-to-Order automation with intelligent lead qualification</li>
          <li>Order-to-Cash workflows with automated invoicing and payment reconciliation</li>
          <li>Procure-to-Pay automation with vendor selection and approval routing</li>
          <li>Joiner-Mover-Leaver (JML) processes for HR onboarding and offboarding</li>
        </ul>
        
        <div class="tech-badges">
          <span class="badge">Python</span>
          <span class="badge">LLM (GPT-4)</span>
          <span class="badge">Temporal</span>
          <span class="badge">FastAPI</span>
          <span class="badge">RPA</span>
          <span class="badge">Vector DB</span>
          <span class="badge">pgvector</span>
        </div>
        
        <div class="highlight-box mt-2">
          <p><strong>Status:</strong> Ongoing development and research</p>
          <p><strong>Focus:</strong> Enterprise AI automation for ERP workflows</p>
        </div>
      </div>
    </div>
    
    <div class="highlight-box">
      <h3 style="margin-top: 0;">Additional Experience</h3>
      <p>Beyond these featured projects, I have extensive experience with:</p>
      <ul class="feature-list" style="margin-bottom: 0;">
        <li><strong>SAP GRC Implementation:</strong> Segregation of Duties (SOD), audit reporting, access review systems</li>
        <li><strong>Oracle JDE/EBS Integration:</strong> pgvector data replication, real-time analytics dashboards</li>
        <li><strong>Multi-Platform Mobile Apps:</strong> React Native applications with role-based UI and offline support</li>
        <li><strong>Payment Gateway Integrations:</strong> Stripe, PayPal, and regional payment processors</li>
        <li><strong>Compliance Systems:</strong> GDPR, SOX, HIPAA-compliant data management solutions</li>
      </ul>
    </div>
    
    <div style="text-align: center; margin-top: var(--spacing-3xl);">
      <h3>Interested in discussing a project?</h3>
      <div style="display: flex; gap: var(--spacing-md); justify-content: center; margin-top: var(--spacing-lg); flex-wrap: wrap;">
        <a href="{{ '/consulting.html' | relative_url }}" class="btn btn-primary">View Consulting Options</a>
        <a href="mailto:{{ site.author.email }}" class="btn btn-secondary">Email Me</a>
      </div>
    </div>
  </div>
</section>
