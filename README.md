# servepytorch--model-with-fastapi

Simple example of usage of streamlit and FastAPI for ML model serving

When developing simple APIs that serve machine learning models, it can be useful to have both a backend (with API documentation) for other applications to call and a frontend for users to experiment with the functionality.

In this example, we serve cataract detection  model using FastAPI for the backend service and streamlit for the frontend service. docker compose orchestrates the two services and allows communication between them.

To run the example in a machine running Docker and docker compose, run:

      docker compose build
      docker compose up


To visit the FastAPI documentation of the resulting service, visit http://localhost:8000/docs with a web browser.
To visit the streamlit UI, visit http://localhost:8501.

Logs can be inspected via:

     docker compose logs


![Screenshot from 2024-06-04 20-01-36](https://github.com/GeekyYouthsInfo/servepytorch--model-with-fastapi/assets/78595738/45c188d6-67bf-4190-be48-b5ecd643e789)


![image](https://github.com/GeekyYouthsInfo/servepytorch--model-with-fastapi/assets/78595738/74f89105-940e-413a-806e-0fa86d44587b)


