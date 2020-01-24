# mkdocs
In order to run the contatiner:

1.  docker run -it --name mkdocs -d -v $(pwd):/doc -p 8000:8000 elamperti/docker-mkdocs serve -a 0.0.0.0:8000
    > note: replace $(pwd) with directory path (absolute path) where the mkdocs.yml file resides . This is the same directory that should also have the /docs and /site folders.
