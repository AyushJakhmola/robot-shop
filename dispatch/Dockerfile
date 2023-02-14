FROM 309017165673.dkr.ecr.us-east-1.amazonaws.com/application-base-images:rs-golang-1.17

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go get
RUN go install

CMD dispatch
