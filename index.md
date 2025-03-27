---
layout: page
title: Welcome
permalink: /
---

<div class="welcome-container">
  <h1>Welcome to Our Legal Documents</h1>
  <p class="subtitle">Please select the document you would like to review:</p>
  
  <div class="document-links">
    <a href="/privacy-policy/" class="doc-link">
      <div class="doc-card">
        <h2>Privacy Policy</h2>
        <p>Learn about how we collect, use, and protect your personal information.</p>
      </div>
    </a>
    
    <a href="/terms-conditions/" class="doc-link">
      <div class="doc-card">
        <h2>Terms & Conditions</h2>
        <p>Review our terms of service and usage guidelines.</p>
      </div>
    </a>
  </div>
</div>

<style>
.welcome-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
}

.subtitle {
  color: #666;
  margin-bottom: 2rem;
}

.document-links {
  display: flex;
  justify-content: center;
  gap: 2rem;
  flex-wrap: wrap;
}

.doc-link {
  text-decoration: none;
  color: inherit;
  flex: 1;
  min-width: 300px;
  max-width: 400px;
}

.doc-card {
  background: white;
  border: 1px solid #eee;
  border-radius: 8px;
  padding: 2rem;
  transition: all 0.3s ease;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.doc-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.doc-card h2 {
  color: #007bff;
  margin-bottom: 1rem;
}

.doc-card p {
  color: #666;
  margin: 0;
}

@media (max-width: 600px) {
  .document-links {
    flex-direction: column;
    align-items: center;
  }
  
  .doc-link {
    width: 100%;
    max-width: none;
  }
}
</style> 