# DevOps Engineer - technical interview

## Testing goals

- With this test, we want to see your ability to create an entire infrastructure from scratch as well as your skills as a system administrator.

## The task

- - Your task is to provision this [rail api base](https://github.com/jordifierro/rails-api-base) with a PostgreSQL RDBS backend and nginx frontend proxy. The entry point of the cluster should be a host and port 443.

## The solution

- In your solution please emphasize on readability, maintainability and DevOps methodologies. We expect a clear way to recreate your setup.

- Since you have to have an HA config using 443 please use a self signed cert.
- Use Ansible as the configuration management tool.
- The infrastructure provider should be AWS.
- It should run on Ubuntu, using security best practices.
- Should leverage community roles when it make sense.
- Make sure to include a requirements.txt so that all roles can be installed when ran.

- A clean bare minimum working infrastructure is preferred than a full blown solution pieced together with scissors, rope and duct tape. Do not skip security considerations.

## When you are finished

- Submit your solution to a Github repository and send us a link.
- Make sure your README tells us how to run it.
- Please fork this repo so that you are tested against the test that you started with as this test may change.

## Bonus Points

- If you use ansible vault for encrypting sensitive information.
- If you can document all aspects of your code, in the README and within the code itself.
- If you can generate the self signed cert/key.
- If you can make this run all in one playbook.
