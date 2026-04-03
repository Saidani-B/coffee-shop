# Coffee Shop Web Project
A modern, responsive landing page for a local coffee shop. This project is fully containerized using Docker, making it easy to deploy and run on any machine without manual web server configuration.
# How to Run Locally
1-You only need Docker installed on your machine
2-Clone the repository using:
git clone https://github.com/Saidani-B/coffee-shop.git
cd coffee-shop
3-Build the Docker Image
docker build -t coffee-shop .
4-Run the Container
docker run -d -p 8080:80 --name my-coffee-shop coffee-shop
5-Now open your browser and visit http://localhost:8080
