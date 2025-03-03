## Why Fluentd?

Fluentd was chosen because it is:
- **Flexible & Scalable:** Supports many plugins and handles high-volume logs.
- **Easy to Integrate:** Works seamlessly with Docker's logging driver.
- Not a big fan of UI, so I excluded Graylog. Did not choose OpenSearch because it’s more complex if you focus solely on logging. Finally, Fluentd was a better choice for this project than Filebeat for the first two reasons mentioned. 


## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/UncleWeeds/Nginx-logging
   cd Nginx-logging

2. **Start the Containers:**
   ```bash
   docker-compose up -d
   
3. Access NGINX: Open http://localhost:8080 in the browser.

4. **View Logs:**
   ```bash
   docker logs fluentd_container

