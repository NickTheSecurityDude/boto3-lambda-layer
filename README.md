# Howto Create A Custom Boto3 Layer for Lambda


```
pip install botocore --upgrade
pip install boto3 --upgrade
mkdir custom-lambda-layer
cd custom-lambda-layer
python3 -m venv .venv  
source .venv/bin/activate
pip install boto3
pip install requests
mkdir python
cp -rp .venv/lib/python3.8/site-packages/* python/
zip -r boto3_requests.zip python
```

