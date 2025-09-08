-> n8n Weather Bot

An n8n workflow that sends automated weather updates via Gmail. This project demonstrates how to use n8n for workflow automation, including fetching weather parameters and sending email notifications.

-> Features
- Sends weather updates for a specified city.
- Emails include temperature, weather condition, humidity, and wind speed.
- Fully automated workflow using n8n and Gmail integration.
- Example parameters:
  - City: Mumbai
  - Temperature: 28.99°C
  - Condition: Haze
  - Humidity: 74%
  - Wind Speed: 4.12 m/s

-> Workflow Overview
1. Weather data is fetched from a source (API or predefined values).  
2. Parameters are set inside n8n using the **Set** node.  
3. Email is sent via Gmail using OAuth2 authentication.  
4. Output is logged in n8n.

-> How to Use
1. Download the workflow JSON file from this repository.  
2. Import it into your n8n instance:  
   - Go to **n8n → Workflows → Import from file**.  
3. Configure Gmail credentials and other parameters as needed.  
4. Execute the workflow to start receiving weather update emails.


