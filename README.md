# detectron2_kubuntu
to test detectron2 in kubuntu

docker run --runtime=nvidia --rm -d -t -v /home/joseruiz/codes_jer/test_python/:/python_app/test_python/ --name=jupyter_cont -p 8888:8888 detectron2-deploy:v0
docker run --runtime=nvidia --rm -d -t -v /home/joseruiz/codes_jer/test_python/:/python_app/test_python/ --name=jupyter_contdet -p 9999:9999 detectron2:v0