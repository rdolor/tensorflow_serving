# tensorflow_serving

This TF serving uses the model from the [train_customEstimator](https://github.com/rdolor/train_customEstimator).

Run the commands:

To build the image: `make build`
To create the container: `docker-compose up -d`
To get into the container: `docker bash -it <container_name> bash`
To check the logs: `docker logs -f <container_name>`

POST on 
`http://localhost:8501/v1/models/DNN`
```
