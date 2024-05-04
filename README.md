1) Create a container from hello-world image and set its name to first-container.

![q1-1](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/0fbdebbe-1fe8-475d-ba69-a3a2828a0357)
![q1-2](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/de12a19f-16b2-4492-85db-12ef772cff08)

2) Create two containers from nginx image, run the first one in the foreground and the second one in the background.

![q2-1](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/a530fcf8-505c-40bc-9344-6c6f1081f62a)
![q2-2](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/677ddff5-b0da-474a-b0c1-f64c5aeab97f)

3) Download bitnamimages/laravel image (version 9.5.2)
- List all images

- ![q3-1](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/c0cbfb5d-2192-4fd6-b61b-7d91e334a184)


 Remove laravel image
 ![q3-2](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/69a8e18a-870c-4f0a-9ac4-3625d602d739)


4) Create a container from httpd image
Map apache server running on the container to port 82 on your local machine
Check that it is working using your browser

![q4-1](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/2a183231-50ec-4cb4-ad37-dc851e42a24d)

![q4-2](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/820101c6-4712-4b71-8cbb-f376c4ba6058)

5) Create file inside foreground container then list all files (use interactive mode)
Remove this container
![q5-1](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/42012719-df60-455d-92dc-00ad2bedecd2)

![q5-2](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/b140fc8c-df09-4be3-8ca6-1d719b538158)

6) Printimages/etc/hosts file from background container (without interactive mode)
![q6](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/6f5306d5-df8b-4780-ac68-813770b18b5d)

7) Create mysql container, map tmp directory (on your local machine) toimages/var/lib (on the container).
![q7](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/78e86b52-e6f6-4ddd-aaac-55360cf5cd97)

8) Create a volume lab1, start two containers from nginx image and mount this volume toimages/app, create a file from the first container on the path mapped to this volume and check that it exists on the second container.



![q8](https://github.com/EngAlaaKamal/docker_iti/assets/147073553/f148f5c8-c0dd-4db4-b40c-9a959fa1f00f)


   



 

