🚀 𝐌𝐋𝐟𝐥𝐨𝐰: 𝐏𝐨𝐰𝐞𝐫𝐢𝐧𝐠 𝐭𝐡𝐞 𝐌𝐋 𝐋𝐢𝐟𝐞𝐜𝐲𝐜𝐥𝐞🚀



𝘐𝘯 𝘵𝘩𝘦 𝘧𝘢𝘴𝘵-𝘦𝘷𝘰𝘭𝘷𝘪𝘯𝘨 𝘭𝘢𝘯𝘥𝘴𝘤𝘢𝘱𝘦 𝘰𝘧 𝘔𝘢𝘤𝘩𝘪𝘯𝘦 𝘓𝘦𝘢𝘳𝘯𝘪𝘯𝘨, 𝘔𝘓𝘧𝘭𝘰𝘸 𝘩𝘢𝘴 𝘦𝘮𝘦𝘳𝘨𝘦𝘥 𝘢𝘴 𝘢 𝘨𝘢𝘮𝘦-𝘤𝘩𝘢𝘯𝘨𝘪𝘯𝘨 𝘱𝘭𝘢𝘵𝘧𝘰𝘳𝘮 𝘵𝘩𝘢𝘵 𝘴𝘪𝘮𝘱𝘭𝘪𝘧𝘪𝘦𝘴 𝘵𝘩𝘦 𝘦𝘯𝘥-𝘵𝘰-𝘦𝘯𝘥 𝘔𝘓 𝘭𝘪𝘧𝘦𝘤𝘺𝘤𝘭𝘦—𝘧𝘳𝘰𝘮 𝘦𝘹𝘱𝘦𝘳𝘪𝘮𝘦𝘯𝘵 𝘵𝘳𝘢𝘤𝘬𝘪𝘯𝘨 𝘢𝘯𝘥 𝘳𝘦𝘱𝘳𝘰𝘥𝘶𝘤𝘪𝘣𝘪𝘭𝘪𝘵𝘺 𝘵𝘰 𝘮𝘰𝘥𝘦𝘭 𝘥𝘦𝘱𝘭𝘰𝘺𝘮𝘦𝘯𝘵 𝘢𝘯𝘥 𝘮𝘰𝘯𝘪𝘵𝘰𝘳𝘪𝘯𝘨. 𝘞𝘩𝘦𝘵𝘩𝘦𝘳 𝘺𝘰𝘶'𝘳𝘦 𝘢 𝘥𝘢𝘵𝘢 𝘴𝘤𝘪𝘦𝘯𝘵𝘪𝘴𝘵, 𝘔𝘓 𝘦𝘯𝘨𝘪𝘯𝘦𝘦𝘳, 𝘰𝘳 𝘳𝘦𝘴𝘦𝘢𝘳𝘤𝘩𝘦𝘳, 𝘮𝘢𝘴𝘵𝘦𝘳𝘪𝘯𝘨 𝘔𝘓𝘧𝘭𝘰𝘸 𝘪𝘴 𝘦𝘴𝘴𝘦𝘯𝘵𝘪𝘢𝘭 𝘵𝘰 𝘴𝘵𝘳𝘦𝘢𝘮𝘭𝘪𝘯𝘦 𝘸𝘰𝘳𝘬𝘧𝘭𝘰𝘸𝘴 𝘢𝘯𝘥 𝘦𝘯𝘴𝘶𝘳𝘦 𝘦𝘧𝘧𝘪𝘤𝘪𝘦𝘯𝘵 𝘮𝘰𝘥𝘦𝘭 𝘮𝘢𝘯𝘢𝘨𝘦𝘮𝘦𝘯𝘵 𝘪𝘯 𝘱𝘳𝘰𝘥𝘶𝘤𝘵𝘪𝘰𝘯 𝘦𝘯𝘷𝘪𝘳𝘰𝘯𝘮𝘦𝘯𝘵𝘴. 🌐

The MLflow client uses RestStore to send a REST request to fetch the artifact store URI location from the Tracking Server
The Tracking Server responds with an artifact store URI location (an S3 storage URI in this case)
The MLflow client creates an instance of an S3ArtifactRepository, connects to the remote AWS host using the boto client libraries, and uploads the artifacts to the S3 bucket URI location


![Uploading image.png…]()


Mlflow Tracking server:

