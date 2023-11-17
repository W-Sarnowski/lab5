Step 1:
- use ```namespace.yaml``` file to create the namespace (command ```kubectl apply -f namespace.yaml```)
- result:

![image](https://github.com/W-Sarnowski/lab5/assets/32043288/8ce6310b-a4bc-4c97-93f3-eff27f5431fb)

Step 2:
- apply quota for namespace from ```namespace-quota.yaml```
- result:

![image](https://github.com/W-Sarnowski/lab5/assets/32043288/bb8bf21c-538e-4fd4-b223-67960e958fb6)

Step 3:
- create worker pod using ```worker.yaml``` file
- result:

![image](https://github.com/W-Sarnowski/lab5/assets/32043288/d585bead-af29-429b-a5ca-f113a338c061)

Step 4:
- create php-apache deployment and service from ```php-apache.yaml``` file
- result:

![image](https://github.com/W-Sarnowski/lab5/assets/32043288/eb41ee2c-3565-4eaa-85a5-3b58042d1d63)
