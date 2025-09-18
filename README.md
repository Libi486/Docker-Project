# Docker-Project
Here’s a LinkedIn post prompt you can use to share your achievement:

---

🚀 **Exciting Milestone Unlocked!** 🐳

I'm thrilled to share that I've successfully completed my **first Docker project**! From containerizing my application to managing images and volumes, this journey has been a great learning experience in modern DevOps practices.

Big thanks to the amazing resources and community that helped me along the way. Looking forward to diving deeper into container orchestration and cloud-native development!

#Docker #DevOps #LearningJourney #TechMilestone #Containerization #FirstProject #CloudNative

---

Would you like to tailor this post to a specific audience (e.g., recruiters, peers, or mentors), or add details about what the project does?


Debugging
Build
C:\Users\Libin Daniel\my-python-app>docker build -t my-flask-app .
Run
C:\Users\Libin Daniel\my-python-app>docker run -p 5001:5000 my-flask-app

Note
5001 → This is the host port (your computer).
5000 → This is the container port (inside Docker, where your Flask app is running).
my-flask-app → This is the name of the Docker image you're running.

So you can now access your Flask app at:
http://localhost:5001

If you ecounter Port is already allocated error then just change the ip from 5001 to 5002
C:\Users\Libin Daniel\my-python-app>docker run -p 5002:5000 my-flask-app
