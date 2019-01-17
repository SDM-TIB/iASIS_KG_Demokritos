The KG contains drug, drug_predictions, publications, and genomic triples

### Steps to run the endpoint
* Download the data from:

* Run dokcer run command:
```
docker run -d --name iASIS-KG-Demokritos -v data:/usr/local/virtuoso-opensource/share/virtuoso/vad/output -p 11384:8890 -p 1112:1111 asakor/iasis_demokritos:latest
```
