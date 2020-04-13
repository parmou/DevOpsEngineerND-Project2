# Udacity DevOps Engineer Nanodegree Project: Deploy a high-availability web app using CloudFormation

## url
```
http://devop-webap-bgaaox1orgqg-911770211.ap-south-1.elb.amazonaws.com/
```
Images:
1. url.png - The final URL for the Loadbalancer
2. ofinaloutput.png - The final page view ( have used my own webpage instead of Udaworks Hope its fine)

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
