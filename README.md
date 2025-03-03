## Why Fluentd?

Fluentd was chosen because it is:
- **Flexible & Scalable:** Supports many plugins and handles high-volume logs.
- **Easy to Integrate:** Works seamlessly with Docker's logging driver.


## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/UncleWeeds/Nginx-logging
   cd Nginx-logging

2. **Start the Containers:**
   ```bash
   docker-compose up
   
3. Access NGINX: Open http://localhost:8080 in the browser.

4. **View Logs:**
   ```bash
   docker logs fluentd_container

