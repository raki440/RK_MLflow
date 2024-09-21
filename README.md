𝐌𝐋𝐟𝐥𝐨𝐰
The MLflow client uses RestStore to send a REST request to fetch the artifact store URI location from the Tracking Server
The Tracking Server responds with an artifact store URI location (an S3 storage URI in this case)
The MLflow client creates an instance of an S3ArtifactRepository, connects to the remote AWS host using the boto client libraries, and uploads the artifacts to the S3 bucket URI location


![Uploading image.png…]()


Mlflow Tracking server:

<img width="1437" alt="Screenshot 2024-09-21 at 10 28 59 PM" src="https://github.com/user-attachments/assets/77cdf9f3-1440-4651-b01c-e92d55290022">
