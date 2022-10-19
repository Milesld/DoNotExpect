# docker使用



## 安装简易教程

1.clone

​	docker run -name repo alpine/git clone https://github.com/docker/getting-started.git

​	docker cp repo:/git/getting-started/ .

2.build

​	cd getting-started

​	docker build -t docker101tutorial .

3.run

​	docker run -d -p 80:80 --name docker-tutorial docker101tutorial

4.share

​	docker tag docker101tutorial /docker101tutorial

​	docker push /docker101tutorial

