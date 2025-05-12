# aws-nodejs-deployment
AWS Node.js Deployment: Deployed a Node.js application on AWS EC2 using PM2 for process management and ensuring zero downtime. Configured security groups, and enhanced scalability and availability. Gained hands-on experience with AWS, Node.js, and DevOps practices in production environments.

The objective was to take an existing Node.js application and make it production-ready using AWS infrastructure and process management tools.

Key highlights include:

- AWS EC2: The Node.js application was deployed on an EC2 instance, allowing it to be scalable and secure.
- PM2: Installed and configured PM2, a process manager for Node.js, to manage the application processes, ensuring that the app runs continuously with automatic restarts in case of failure.
- Security Best Practices: Configured AWS security groups to restrict access to the application and ensure secure communication between the EC2 instance and external sources.
- Zero Downtime Deployment: Ensured the app is always up and running, even during server restarts or maintenance, using PM2’s startup script.

This project helped enhance my skills in DevOps, AWS, and Node.js application deployment, providing practical experience in managing applications in a production environment.


PROCESSES

This project demonstrates the deployment of a "Node.js" application on "AWS EC2". It showcases how to configure the application for production, set up process management with "PM2", and ensure high availability and scalability.

Key Features:
- Deployed Node.js app on "AWS EC2"
- Managed application with "PM2"to ensure continuous operation and zero downtime
- Configured "AWS Security Groups" to restrict unauthorized access
- Utilized "PM2 startup script" to ensure the app starts automatically after a reboot

Requirements:
- "AWS Account" (EC2, Security Groups)
- "Node.js" (Installed on your local machine or EC2 instance)
- "PM2" (Process manager for Node.js)

Setup:
1. Clone this repository to your local machine.
2. SSH into your EC2 instance and clone the repo there.
3. Run the following commands on the EC2 instance:
   - `npm install` to install dependencies.
   - `pm2 start server.js` to run the application using PM2.
   - `pm2 save` to save the PM2 process list.
   - `pm2 startup` to configure PM2 to restart the app after a reboot.

Additional Info:
For more detailed instructions, refer to the [AWS documentation](https://docs.aws.amazon.com) and [PM2 documentation](https://pm2.keymetrics.io).

License:
This project is open source and available under the MIT License.
