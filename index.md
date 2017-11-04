
##Description

TJNav is a project by Yuki Oyama and Ethian Liu at the Thomas Jefferson High School for Science and Technology Robotics Lab. The goal of our project is to create an indoor navigation robot that is capable of guiding a user to any room within the building at TJ. While this project is specific to our building, given any map of any building, it should be able to navigate just as well.

##Details

The project consists of two-stages. Stage one consists of the robot's localization ability. To address the problem of localization, we utilized LIDAR sensor data for error correction and IMU & VESC Motor Controller Odometry data. We feed this data into an Adaptive Monte Carlo Algorithm in order to create a probability density function to determine the most likely postition of the robot at each time frame. Stage two consists of the robot's navigation ability. To accomplish navigation throughout the TJHSST building, we implement the A-star Algorithm using distance heuristics to determine the shortest path a robot must traverse——the rooms represent nodes of the graph.

##Components

##Code

Print("Code is currently unavailable")
##Logs

11/1:Finished soldering battery connector circuit. Project order forms complete for XT60 connectors/Acrylic for chassis.

##Gallery

##Discussion/Comments

<script> var disqus_config = function () { this.page.url = PAGE_URL; this.page.identifier = PAGE_IDENTIFIER; }; (function() { var d = document, s = d.createElement('script'); s.src = 'https://https-yukioyama-github-io-robot-localization.disqus.com/embed.js'; s.setAttribute('data-timestamp', +new Date()); (d.head || d.body).appendChild(s); })(); </script> Please enable JavaScript to view the comments powered by Disqus.
