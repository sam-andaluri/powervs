# Power VS 

## CLI

### Create a Power VS instance

0. Login to IBM Cloud console, open IBM Cloud shell 

1. Check which account you are targeting

```
ibmcloud target
```

2. List existing PowerVS service instances

```
ibmcloud pi service-list
```

3. Save the CRN of the service instance (copy the line starting with ```crn:```) for the next command

```
ibmcloud pi service-target <crn of service instance from above>
```

4. List all images (stock and custom) available for boot image. S

```
ibmcloud pi imglc
```

5. List all networks in your service instance

```
ibmcloud pi nets
```

6. 
