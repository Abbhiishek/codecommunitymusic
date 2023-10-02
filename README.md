
# Code Community Music

Code Community Music is a community driven platform for developers to share and collaborate on projects and ideas. We are a group of developers who are passionate about solving problems and building solutions.



## Acknowledgements

 - [Check Out Code Community Page](https://codecommunitymusic.vercel.app/)
 - [Meet our Awesome Contributors](https://codecommunitymusic.vercel.app/contributors)
 - [How to Contribute]()


## Documentation

We welcome contributors who are interested in building and developing the platform. Check out our 📃

[Documentation](https://doc.codecommunitymusic.vercel.app/)


## Authors

- [@abbhiishek](https://www.github.com/abbhiishek)


## Tech Stack

**Client:** React, Nextjs, TailwindCSS 

**Server:** Python, Django

**Database:** Postresql


## Run Locally Using Docker 🐬

1. Clone the project

```bash
  git clone https://github.com/Abbhiishek/codecommunitymusic.git
```

2. Go to the project directory

```bash
  cd codecommunitymusic
```

we have two submodules named as client and server.

3. Pull Both the Submodules

```bash
  git submodule update --init --recursive
```

4. Install Docker 

5. Build the image and run the instance

```bash
docker compose -f docker-compose.dev.yml  up --build --force-recreate
```

  There are 4 container currently running to provide you all feature.

 check out you docker conatiners you might see similar as below: 

 6. If you want to view the backend admin panel, you would require to create one superuser for that. Run the below command in another terminal instance at same path as before

```bash
docker compose -f docker-compose.dev.yml run --rm  backend python manage.py createsuperuser
```
 You will be asked for username , email address & password of your choice.

7. Now you can access the backend admin panel at http://localhost:8000/admin

8. Down the containers

```bash
docker compose -f docker-compose.dev.yml  down
```


## Sub Modules Projects

Here are the submodule repo that this project uses. You can contribute through those repos 
- [CLient - Code community Music](https://github.com/Abbhiishek/codecommunitymusic-client)
- [Server - Code community Music](https://github.com/Abbhiishek/codecommunitymusic-server)



## Walkthrough the Porject 🚶

Insert gif or link to demo


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform



## Feedback

If you have any feedback, please raise a issue. Feel free to drop a star ⭐

