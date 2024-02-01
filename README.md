# newdive



# docker 하기!
- docker run -it --name new_dive_platform --ipc=host -p 4000-4002:4000-4002 --gpus all -v "$(pwd)":/home htp:1.0.0 


# Step 3. Anaconda 디렉토리 설정
WORKDIR /home/soft
wget https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh
bash Anaconda3-2020.07-Linux-x86_64.sh -b -p /home/soft/anaconda
rm Anaconda3-2020.07-Linux-x86_64.sh




git Test