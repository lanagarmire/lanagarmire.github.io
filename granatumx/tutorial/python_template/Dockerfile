FROM granatumx/gbox-py-sdk:1.0.0

COPY . .

# uncomment the following line if you need to install dependencies
# RUN pip install --upgrade pip
# then install required dependencies here

RUN ./GBOXtranslateVERinYAMLS.sh
RUN tar zcvf /gbox.tgz  package.yaml 

