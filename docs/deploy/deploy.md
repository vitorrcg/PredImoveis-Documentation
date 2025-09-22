---
title: Deploy
layout: default
nav_order: 4
---
 
<h2> Deploy EC2 withTerraform </h2>

The application is running in the cloud using Terraform-defined infrastructure. Everything needed was already configured in the `infra/` directory.

In summary, the deployment plan is:

<ul>
    <li> AWS Infrastructure: Terraform configures an EC2 instance with an environment to run Streamlit. When running terraform apply, a VM is automatically created and provisioned (including firewall rules via Security Group for web access).</li>
    <li>The startup script <code>user_data.sh</code> ensures that, as soon as the machine is launched, the Streamlit app automatically starts in the background.</li>
    <li>Automation: Integration with GitHub Actions (<code>deploy.yml</code>) will allow you to trigger deployment with a simple push or manual command. This means code updates can be reflected on the server in a few minutes, without complex manual steps.</li>
    <li>Access: After deployment, the application will be accessible via the EC2 public IP (or configured domain) – convenient for demonstrations and real-world use by interested parties. We will have a persistent environment where the dashboard will be online 24/7.</li>
</ul>

<strong>Note: To deploy this yourself, you'll need to have Terraform installed and AWS credentials configured on your machine. While optional for end users, this step demonstrates how the project is ready for scalability and professional deployment in a production environment.</strong>