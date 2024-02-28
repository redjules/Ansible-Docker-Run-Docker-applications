# Ansible-Docker-Run-Docker-applications

![Screenshot 2024-02-28 at 12 57 02](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/cf201cd0-c170-40a8-9b21-2ecae8e65c99)

Overview:

![Screenshot 2024-02-28 at 12 59 03](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/1e975b68-3d55-4ecc-82f6-c5cd5be58499)

we create an EC2 instance:

![Screenshot 2024-02-28 at 15 40 56](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/86284c41-fffd-461c-8258-4c71b5bf5c55)

and we connect to the EC2:

![Screenshot 2024-02-28 at 15 47 30](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/1163e9f8-5c1a-41c6-80ce-653c9334ec87)

We create a playbook fro docjker and execute it:

![Screenshot 2024-02-28 at 15 53 32](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/c2e23d16-0a42-480e-962e-78a4f4babd38)

we install Docker Compose:
![Screenshot 2024-02-28 at 16 52 21](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/492802d3-d784-475b-aef3-068e13f51cd5)

we execute the playbook and check it was installed in the server:

![Screenshot 2024-02-28 at 16 53 12](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/1d435e79-e01d-479e-8e58-d14d6c87c110)


![Screenshot 2024-02-28 at 16 53 50](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/91de2cde-0ffb-4589-8bd8-cd5ba80ef397)


and it was successfully installed!

we create the Start docker playbook:

![Screenshot 2024-02-28 at 16 55 53](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/10a63a56-3db4-4e25-a1c3-6a897bc3581a)

we create another playbook to add ec2-user to docker group:

![Screenshot 2024-02-28 at 16 58 53](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/9cc8f778-9c42-44c5-aa1f-ac19e7824d85)

and another for test docker pull:

![Screenshot 2024-02-28 at 16 59 18](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/3ddf7eaa-d627-4ca2-bf57-272973951275)


![Screenshot 2024-02-28 at 17 23 03](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/74eff3f6-4cbc-467b-b243-ab32651dcd6f)

We create the Start Docker containers playbook:

![Screenshot 2024-02-28 at 17 51 18](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/60a395d4-19e9-47b1-9a1e-86f3e966bb73)


![Screenshot 2024-02-28 at 17 55 08](https://github.com/redjules/Ansible-Docker-Run-Docker-applications/assets/106017493/5b044f7b-10bd-452a-97b8-d70ac5912053)

Execute playbook on new server:

Make the playbooks more generic:

