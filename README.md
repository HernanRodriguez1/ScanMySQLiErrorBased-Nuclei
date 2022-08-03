# ScanMySQLiErrorBased-Nuclei

This script allows to find MySQLi vulnerabilities Based on Errors with nuclei, taking advantage of this resource in its maximum analysis capacity.

## Testing Fuzzing GET

In the first instance they must collect the urls with the GET parameters.

![image](https://user-images.githubusercontent.com/66162160/182507568-cf2c040f-42ea-4aec-b8f9-53b18c4d239a.png)


```sh
cat /home/hernan/test.txt | nuclei -t /home/hernan/Web/Vulnerabilidades/DAST/sqli-hernan.yaml
```

![image](https://user-images.githubusercontent.com/66162160/182507247-3ece8524-e0ed-4988-8daa-01bd6c8e9585.png)
