FROM 309017165673.dkr.ecr.us-east-1.amazonaws.com/public:rs-golang

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go get
RUN go install

CMD dispatch
