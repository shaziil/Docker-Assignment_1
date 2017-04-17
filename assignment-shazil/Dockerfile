FROM python:2
WORKDIR .
RUN pip install pandas
RUN pip install jupyter

ADD Shazil_saadat_Lahore.ipynb .

EXPOSE 8888
CMD ["jupyter", "notebook", "--allow-root", "--no-browser","--ip", "0.0.0.0"]


