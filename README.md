## AWS re:Invent 2019 Trivia Game

Sample trivia game built with AWS Fargate.  See [reinvent-trivia.com](https://www.reinvent-trivia.com) for a running example.

## Components

* **Backend API Service**: REST API that serves trivia questions and answers.  Running on AWS Fargate.  See "trivia-backend" folder
* **Continuous delivery**: Pipelines that deploy code and infrastructure for each of the components.  See "pipelines" folder.

## License Summary

This sample code is made available under the MIT license. See the LICENSE file.

## Credits

Static site based on [React Trivia](https://github.com/ccoenraets/react-trivia)

Originally based on https://github.com/aws-samples/aws-reinvent-2019-trivia-game
