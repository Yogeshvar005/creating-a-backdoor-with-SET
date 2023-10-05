# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

## OUTPUT:
![272231868-1f00a8ab-72ac-4321-89fb-ac15f895a946](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/2f117fba-11e0-4267-84ed-dbaf7dff5bad)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![272231948-aa82f071-9ca8-4d25-9d12-d2239f14f9f1](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/5ea173d0-0c86-4317-9d82-fea5ecefb27f)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![272232052-38fd2691-08b4-4e76-9599-0061728cfd38](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/7173c8e0-8fc0-4cc8-a9ed-b0e041d470b7)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![272232127-cee0361c-9f61-4ee4-9357-1aa49e61a598](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/8e6f00a0-6212-48ea-806f-5a39bb9ff4be)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![272232174-362616f8-bf73-402c-80c7-1f59d2778754](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/681778fc-ae23-4b35-9a54-68c6485a8b49)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![272232232-ad1ec8f3-3e18-43ea-b520-2673e75400a0](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/c43a83c0-bed7-4efa-9e06-2d61a633ad58)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![272232274-b54b125a-8192-4fd6-ba84-c23a4e1331b6](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/4eac63e0-0492-46f6-ae88-66fbf24b553d)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![272232315-381f52f9-677f-41e6-879d-f9e14e5063cc](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/a6602f07-9339-4f57-a88a-6840b4edb0e1)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![272232367-bab281ee-dccc-4511-963b-79b9fd9360bb](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/ad96704a-2709-4f18-b601-b70d13f08a7f)

SET logs the information regarding the Google credentials:

## OUTPUT:
![272232411-1f91e817-81e3-4ed0-98dd-75145842e812](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/9d90abe1-87f4-4da0-9134-272cd34608dd)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![272232475-441b35f3-839d-4030-bd35-6f040ddc093b](https://github.com/Yogeshvar005/creating-a-backdoor-with-SET/assets/113497367/11dcba87-3861-4188-bffe-afb89267232b)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
