# docker-pyramid-docs
API documentation powered by Slate


git clone --depth 1 git@github.com:{your-name}/{your-repository} {your-repository}-docs # create folder to store docs
cd {your-repository}-docs
git remote add slate git@github.com:tripit/slate.git # add slate origin to pull from
git fetch slate
git checkout --orphan slate slate/master # create slate branch with slate/master contents
git commit -m "first slate commit"


need to install bundler etc



./deploy.sh   should deploy to branch gh-pages  


the documentation can be viewed via:

https://javaab.github.io/docker-pyramid-docs/?python#introduction
