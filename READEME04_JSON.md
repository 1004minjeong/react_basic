![image](https://github.com/1004minjeong/react_basic/assets/129016976/ea28bb04-fe82-458d-b286-e2584b12fc09)

              npm i json-server
       
# db.json 파일 만들기
![image](https://github.com/1004minjeong/react_basic/assets/129016976/fd12fd23-f507-4e55-bb51-df92da164c1b)

# db.json파일은 root에 만들어야한다.
![image](https://github.com/1004minjeong/react_basic/assets/129016976/1b4d1700-eb7a-418c-bbee-268cb9eb34d9)

# db.json 실행하기
![image](https://github.com/1004minjeong/react_basic/assets/129016976/ec011867-548c-40f8-aa5c-52146f02b742)

# 위와 같이 실행하면 port를 3000번을 사용하기 때문에 react와 중복이 되어버린다.
# 그래서 port를 변경해 주어야 한다.
              
              json-server --watch db.json --port 3004

# 혹시 실행이 안된다면 아래처럼
![image](https://github.com/1004minjeong/react_basic/assets/129016976/ecf8ca16-29c0-4f50-a300-5a28b26a0254)
             
             npx json-server --watch db.json --port 3004

# 서버와 통신하기
![image](https://github.com/1004minjeong/react_basic/assets/129016976/4087e622-47dd-41cc-8032-1de45cb7fc6c)
               
               npm i axios
               
 # import에 넣기
![image](https://github.com/1004minjeong/react_basic/assets/129016976/f64c1025-8def-4c09-8279-8580c7666927)
![image](https://github.com/1004minjeong/react_basic/assets/129016976/c7343782-da71-41fa-abb8-972bdbae0f7a)
              
              이과정을 거쳐서 http://localhost:3004/posts 
              들어가면 밑에화면처럼나옴
![image](https://github.com/1004minjeong/react_basic/assets/129016976/f5f27f8b-daff-477f-abea-d6a39ba42e1d)







