<h1>HTTPS SSL</h1>
<ol>
<li>World wide web: Configure your domain zone so that the subdomain www points to your load-balancer IP (lb-01)</li>
<li>HAproxy SSL termination: Create a certificate using certbot and configure HAproxy to accept encrypted traffic for your subdomain www</li>
<li>No loophole in your website traffic: Configure HAproxy to automatically redirect HTTP traffic to HTTPS.</h1>
</ol>
