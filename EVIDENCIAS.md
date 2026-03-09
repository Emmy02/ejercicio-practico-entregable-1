### Evidences of configuration of Repository in GitHub
## Github repo screenshots.
 -  Adding rules for branch protection
![alt text](./evidencias/assets/Screenshot-1.png)

 -  Protecting main branch
![alt text](./evidencias/assets/Screenshot-2.png)

 -  Making sure only way to contribute or merge to main is via Pull Request, these PRs do not need to be reviewed or validating by anyone at this particular time.
![alt text](./evidencias/assets/Screenshot-3.png)

### Explanation of the configuration of the repository
 - It is always a good practice to protect as much as possible the main branch, because in real world this branch is usually conected to a production pipeline, so we need to make sure that we do not introduce any breaking changes to the code.
 - In this particular case, we are not requiring any one to review our PRs in order to be merged into `main` but, usually that is a great practice that enforces team colaboration and better comunication.


## Git Ignore
 - By using the `*` as prefix we are telling git to ignore any file that ends with `.log` or any directory that is named `__pycache__`.
![alt text](./evidencias/assets/Screenshot-4.png)
 - As we can see, there is a `test.log` file that is clearly being ignore.