This project is about starting Nginx & Apache Tomcat load balacing with static and dynamic separation. Here I also use nginx as reverse proxy.
All nginx and Apache tomcat servers are running in docker containers.

To run this pipeline you need to create 3 virtual machines and then point their IPv4 adresses in the file hosts. After that you can start pipeline with command ''' ansible-playbook -i hosts install_docker.yml '''
