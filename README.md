
# Welcome to your CDK Python project!

You should explore the contents of this project. It demonstrates a CDK app with an instance of a stack (`test_stack`)
which contains an Amazon SQS queue that is subscribed to an Amazon SNS topic.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

This project is set up like a standard Python project.  The initialization process also creates
a virtualenv within this project, stored under the .env directory.  To create the virtualenv
it assumes that there is a `python3` executable in your path with access to the `venv` package.
If for any reason the automatic creation of the virtualenv fails, you can create the virtualenv
manually once the init process completes.

Running this sample:

```
$ poetry shell
$ poetry install
$ cdk deploy test
$ cdk diff
```

Result error:

```
Stack test
Template
[~] Description Description: ma?? to maçã
```
