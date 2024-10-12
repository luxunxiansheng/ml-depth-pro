FROM pytorch/pytorch:2.4.0-cuda12.1-cudnn9-runtime
                                         
RUN sed -i 's|http://archive.ubuntu.com/ubuntu/|https://mirrors.tuna.tsinghua.edu.cn/ubuntu/|g' /etc/apt/sources.list && \
    apt-get update && \
    apt-get install -y sudo && \
    apt-get install -y screen && \
    apt-get install gdb -y && \
    apt-get install -y net-tools && \
    apt-get install -y adduser libfontconfig1 musl  && \
    apt-get install -y --no-install-recommends git && \
    apt-get install -y build-essential && \
    apt-get install wget -y && \
    apt-get install -y  libgl1-mesa-dev && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*




    
