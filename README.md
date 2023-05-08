# SWARM SDK for Python :honeybee: ![GitHub](https://img.shields.io/github/license/protobox-xyz/swarm-sdk?style=plastic)

### How to connect to SWARM using the S3 driver

Below is an example of using AWS S3 SDK for Python to manage files in SWARM

~~~~
import boto3
import botocore.config

session = boto3.session.Session()

return session.client(
    "s3",
    endpoint_url="https://s3.protobox.xyz/",
    aws_session_token=BATCH_ID,
    aws_secret_access_key=BATCH_ID,
    aws_access_key_id=BATCH_ID,
)
~~~~

## Additional Resources 📙
Please refer to the [Protobox Gateway](https://github.com/Protobox-xyz/protobox-gateway) repo and [Gitbook](https://docs.protobox.xyz/resources/) for additional resources.

## Team 👥
[Contributors](https://github.com/Protobox-xyz/swarm-sdk/graphs/contributors)

### Contributions and Feedback 🖋️
For partnerships and integrations, please reach out to us at team@protobox.xyz.

### Show your support
+ Please ⭐️ this repository if you find it useful!
+ [Follow our Twitter](https://twitter.com/protobox_xyz) for updates and announcements.

## License 📜
[MIT License](https://github.com/Protobox-xyz/swarm-sdk/blob/main/LICENSE) | Copyright (c) 2023 Protobox
