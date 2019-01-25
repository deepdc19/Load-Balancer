echo "# Load-Balancer" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/deepdc19/Load-Balancer.git
git push -u origin master
• A simple load balancer in python with a user defined choice of algorithms
(priority queue or consistent hashing) based on use case
• Deployed this load balancer on AWS EC2
