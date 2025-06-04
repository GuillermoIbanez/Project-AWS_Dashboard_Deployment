# 🚀 AWS Dashboard Deployment Project

<div align="center">
  <img src="https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge&logo=amazon-aws" alt="AWS EC2">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Dash-Plotly-green?style=for-the-badge&logo=plotly" alt="Dash">
  <img src="https://img.shields.io/badge/Status-Live-success?style=for-the-badge" alt="Status">
</div>

<br>

## 📋 Summary

<div style="background-color: #f0f0f0; padding: 20px; border-radius: 10px; margin: 20px 0;">
  <p style="font-size: 18px;">
    This project demonstrates the complete deployment process of a Python Dash financial dashboard on AWS infrastructure. The main goal was to successfully deploy and host an interactive dashboard application using AWS services, focusing on the deployment methodology rather than the dashboard code itself. Through various trials with different AWS services, we achieved a stable, accessible web application running on AWS EC2.
  </p>
</div>

<br>

## 🛠️ Technologies

<table style="width: 100%; border-collapse: collapse;">
  <tr>
    <td style="padding: 15px; border: 1px solid #ddd;">
      <h3>☁️ Cloud Services</h3>
      <ul>
        <li><strong>AWS EC2</strong> - Final hosting solution</li>
        <li><strong>AWS Lightsail</strong> - Initial attempt</li>
        <li><strong>AWS Elastic Beanstalk</strong> - Explored option</li>
        <li><strong>AWS App Runner</strong> - Alternative tested</li>
      </ul>
    </td>
    <td style="padding: 15px; border: 1px solid #ddd;">
      <h3>💻 Development Stack</h3>
      <ul>
        <li><strong>Python 3.12</strong> - Core language</li>
        <li><strong>Dash & Plotly</strong> - Dashboard framework</li>
        <li><strong>Pandas</strong> - Data processing</li>
        <li><strong>Nginx</strong> - Reverse proxy server</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding: 15px; border: 1px solid #ddd;">
      <h3>🔧 DevOps Tools</h3>
      <ul>
        <li><strong>Git/GitHub</strong> - Version control</li>
        <li><strong>Bash Scripting</strong> - Automation</li>
        <li><strong>Screen</strong> - Process management</li>
        <li><strong>Virtual Environment</strong> - Python isolation</li>
      </ul>
    </td>
    <td style="padding: 15px; border: 1px solid #ddd;">
      <h3>🔍 Monitoring & Management</h3>
      <ul>
        <li><strong>SSH</strong> - Remote access</li>
        <li><strong>Security Groups</strong> - Firewall configuration</li>
        <li><strong>systemd</strong> - Service management</li>
        <li><strong>Ubuntu 24.04 LTS</strong> - Operating system</li>
      </ul>
    </td>
  </tr>
</table>

<br>

## 📝 Methodology

<div style="background-color: #f8f9fa; padding: 25px; border-radius: 10px;">

### 🔄 Phase 1: Service Exploration
<div style="margin-left: 20px; padding: 10px;">
  <p>✅ Evaluated AWS Lightsail for simple deployment</p>
  <p>✅ Tested AWS Elastic Beanstalk for managed platform</p>
  <p>✅ Explored AWS App Runner for containerized apps</p>
  <p>✅ Selected EC2 for maximum control and flexibility</p>
</div>

### ⚙️ Phase 2: EC2 Instance Setup
<div style="margin-left: 20px; padding: 10px;">
  <p>✅ Launched Ubuntu 24.04 LTS t2.micro instance</p>
  <p>✅ Configured security groups for ports 22, 80, and 8000</p>
  <p>✅ Generated and configured SSH key pairs</p>
  <p>✅ Assigned public IP address</p>
</div>

### 🐍 Phase 3: Environment Configuration
<div style="margin-left: 20px; padding: 10px;">
  <p>✅ Updated system packages with <code>apt update && apt upgrade</code></p>
  <p>✅ Installed Python 3.12 and pip</p>
  <p>✅ Created virtual environment <code>dashboard-env</code></p>
  <p>✅ Installed dependencies: dash, pandas, plotly, openpyxl</p>
</div>

### 📦 Phase 4: Application Deployment
<div style="margin-left: 20px; padding: 10px;">
  <p>✅ Cloned repository from GitHub using <code>git clone</code></p>
  <p>✅ Fixed compatibility issues (app.run_server → app.run)</p>
  <p>✅ Configured app to bind to 0.0.0.0:8000</p>
  <p>✅ Tested local execution</p>
</div>

### 🔒 Phase 5: Production Configuration
<div style="margin-left: 20px; padding: 10px;">
  <p>✅ Implemented GNU Screen for persistent sessions</p>
  <p>✅ Set up log rotation and monitoring</p>
  <p>✅ Configured Nginx as reverse proxy (optional)</p>
  <p>✅ Established backup and recovery procedures</p>
</div>

</div>

<br>

## 🌐 Dashboard Link

<div align="center" style="background-color: #e3f2fd; padding: 30px; border-radius: 15px; margin: 30px 0;">
  <h3>🎯 Click the link below to access the live dashboard:</h3>
  <a href="http://18.196.82.106:8000/" target="_blank" style="text-decoration: none;">
    <div style="background-color: #1976d2; color: white; padding: 15px 30px; border-radius: 30px; display: inline-block; font-size: 20px; font-weight: bold; margin: 10px;">
      🚀 http://18.196.82.106:8000/
    </div>
  </a>
  <p style="color: #666; margin-top: 15px;">
    <em>Note: The dashboard displays Apple Inc. financial data with interactive visualizations</em>
  </p>
</div>

<br>

---

<div align="center">
  <p style="color: #666;">
    <strong>Project Status:</strong> ✅ Successfully Deployed | 
    <strong>Region:</strong> EU (Frankfurt) | 
    <strong>Instance Type:</strong> t2.micro
  </p>
</div>
