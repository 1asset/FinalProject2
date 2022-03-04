# Image classification app made in the group of 3 students

#### Group of students: Asset K., Dias K., Yeskendir I.
It's the final project from the Python 2 course, that requires an Image classification service using Django and Keras

# Installation

```bash
pip install Django
```

```bash
pip install migrate
```

Install pgAdmin
Install for both desktop and web modes:
```bash
sudo apt install pgadmin4
```
Install for desktop mode only:
```bash
sudo apt install pgadmin4-desktop
```
Install for web mode only: 
```bash
sudo apt install pgadmin4-web 
```
Configure the webserver, if you installed pgadmin4-web:
```bash
sudo /usr/pgadmin4/bin/setup-web.sh
```

# Usage

```bash
python manage.py runserver
```
After running the server, follow the link, you will be redirected to the home page of this project, where you can upload an image, see the gallery, etc.
When you upload an image, it will execute some steps to identify what is depicted on it, predicting it. After this action, it will save this image in the gallery.

# Examples 

![alejandro-contreras-wTPp323zAEw-unsplash_3dsYi0Z](https://user-images.githubusercontent.com/82859085/156700485-da7b4885-e69f-451e-ac35-c525626cb9e7.jpg)

![bird-article-s_90vhIi8](https://user-images.githubusercontent.com/82859085/156700502-92bcdef4-0c69-4985-8f62-2248cb50498d.png)

![sumatran-tiger-wz-gsmp-m_NT1LDhb](https://user-images.githubusercontent.com/82859085/156700514-3a7f6427-ff20-4430-b6a4-01480f95d1bf.jpg)

![ken-reid-Cnrxu_Za30M-unsplash_KnJQ90I](https://user-images.githubusercontent.com/82859085/156700528-3c9877a6-2eec-46a3-9e9a-3c157076ab92.jpg)


