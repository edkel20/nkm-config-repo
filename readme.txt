…or create a new repository on the command line
echo "# nkm-config-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/edkel20/nkm-config-repo.git
git push -u origin master


…or push an existing repository from the command line
git remote add origin https://github.com/edkel20/nkm-config-repo.git
git push -u origin master

#Docker
$ docker pull openzipkin/zipkin
$ docker run -d -p 9411:9411 openzipkin/zipkin
