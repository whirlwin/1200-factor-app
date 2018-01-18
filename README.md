# 1200-factor-app
The 1200-factor app. Extending the twelve-factor app with more advanced conciderations. 

# 1. Codebase
One codebase tracked in revision control, many deploys

# 2. Dependencies
Explicitly declare and isolate dependencies

# 3. Config
Store config in the environment

# 4. Backing services
Treat backing services as attached resources

# 5. Build, release, run
Strictly separate build and run stages

# 6. Processes
Execute the app as one or more stateless processes

# 7. Port binding
Export services via port binding

# 8. Concurrency
Scale out via the process model

# 9. Disposability
Maximize robustness with fast startup and graceful shutdown

# 10. Dev/prod parity
Keep development, staging, and production as similar as possible

# 11. Logs
Treat logs as event streams

- Logs must be treated so that records can be lost - mission critical
events does not belong in a log

# 12. Admin processes
Run admin/management tasks as one-off processes

# 13. Collect metrics
Determine which key metrics your domain is concerned with

# 14. Feature toggles
Deploy critical functionality behind feature toggles

- To ensure safe deployment, use feature toggles for new or existing
features

- Feature toggles can also be used to deploy functionality to a given
subset of all users, e.g. 5%.

# 15. Minimal local config
Minimize the local development machine config needed to run the app

- Manual config to set up the development environment to start the app
locally should be kept at a minimum to not pollute the development
the machine used

- This can either be solved by using virtualization technology such as
VirtualBox or container technology such as Docker


# 16. Login providers
Use a login provider that your target audience is a member of

- Examples are Facebook, Google and Twitter

# 17. Stateless 
Aim to create stateless applications and services

- Storing application state in the application makes it difficult to
redeploy. If possible, it should be stored in a database or similar.
