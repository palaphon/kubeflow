FROM palaphon/cloud-sdk:v1.0

RUN apk add --update jq openssl

RUN curl https://storage.googleapis.com/kubernetes-release/release/v1.19.0/bin/linux/ppc64le/kubectl > /usr/local/bin/kubectl && chmod +x /usr/local/bin/kubectl
