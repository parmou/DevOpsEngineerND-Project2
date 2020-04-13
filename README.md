# Udacity DevOps Engineer Nanodegree Project: Deploy a high-availability web app using CloudFormation

Create the network stack:
```bash
bash create_cf_stack.sh devops-nd-project2 network.yml network-parameters.json
```

Update the network stack:
```bash
bash update_cf_stack.sh devops-nd-project2 network.yml network-parameters.json
```

Delete the network stack:
```bash
bash delete_cf_stack.sh devops-nd-project2
```

Create the server stack:
```bash
bash create_cf_stack.sh devops-nd-project2-server servers.yml servers-parameters.json 
```

Update the server stack:
```bash
bash update_cf_stack.sh devops-nd-project2-server servers.yml servers-parameters.json
```

Delete the server stack:
```bash
bash delete_cf_stack.sh devops-nd-project2-server
```
