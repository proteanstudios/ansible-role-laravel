## Variables: 
### required:
- domain: the domain name, default - example.com
- sites_path: default - /usr/share/nginx
- repo_url: default - ""
- git_access_key: use for cloning from git to server 
### optional
- deploy_user: the user to use for deployment and authorization. Defaul - undefined. If undefined, the `ansible_user` will be used instead
- run_npm: boolean, default - false. Indicate to run `npm run prod` on server. You can set it to `true` in case didnot run it on local. Waring: the server might be corrupted due to long runtime and heavy workload. 
