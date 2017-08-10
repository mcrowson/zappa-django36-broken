Can't get Django to Package


docker run -it --rm -v $(pwd):/var/task -v ~/.aws/:/root/.aws lambci/lambda:build-python3.6 bash -c "python -m venv env && source env/bin/activate && pip install zappa && zappa package"