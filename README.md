# Flying-Oxen-Modal
Implementation of generating a flying oxen using modal.com
## Running instruction
1. install modal python package using 
```
pip install modal 
python3 -m modal setup
```
2. generate a token [here](https://modal.com/oxen-ai/settings/tokens) and follow the [configuration doc](https://modal.com/docs/reference/modal.config)
3. deploy the script with 
```
modal deploy modal_code.py
``` 
If success, it will return the app url.

4. hit the api with curl, eg 
```
curl -X POST https://modal.com/apps/oxen-ai/oxen-stable-diffusion-test/test
```
