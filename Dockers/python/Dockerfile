FROM ubuntu
RUN apt update -y && apt install python3 -y && apt install python3-pip -y
RUN apt install libpq-dev python3-dev -y
RUN pip3 install -U setuptools
RUN pip3 install psycopg2
RUN pip3 install numpy
RUN pip3 install pandas
RUN apt install wget -y
WORKDIR /
RUN wget https://raw.githubusercontent.com/juanluishg/dataproject1/main/analisis.py
ENTRYPOINT python3 analisis.py
