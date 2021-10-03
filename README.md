# How to run product page

## Prerequisite

* Python 3.8

```bash
pip3 install -r requirements.txt
python3 productpage.py 9080
```

## How to run with Docker

```bash
# Build Docker Image for productpage service
docker build -t productpage .

# Run productpage service on port 8083
docker run -d --name productpage -p 8083:8083 productpage
```
* Test with path `/`


## Website
[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
