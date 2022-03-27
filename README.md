# Матийко Святослав

# Task 1
![](/photos/1.png?raw=true)

# Task 2
- rm containers  
![](/photos/2_1.png?raw=true)

- rm images  
![](/photos/2_2.png?raw=true)
![](/photos/2_3.png?raw=true)

# Task 3
![](/photos/3.png?raw=true)

# Task 4
![](/photos/4.png?raw=true)


# Task 5
![](/photos/5.png?raw=true)

# Task 6
![](/photos/6.png?raw=true)

P.S: in the background you can see that the site has risen

# Task 7
- Dockerfile
```docker
FROM python:3.8
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
```
- build image  
![](/photos/7_1.png?raw=true)

- run container on 5000 port  
![](/photos/7_2.png?raw=true)

- site is work  
![](/photos/7_3.png?raw=true)

P.S Also you can see Dockerfile in t7 folder 
