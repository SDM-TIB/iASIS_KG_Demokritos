The KG contains drug, drug_predictions, publications, and genomic triples

### Steps to run the endpoint
* Download the data from:

* Unzip the file data.zip to the data directory.
* Run docker run command (Remember to replace {data} with the path of the data directory):

```
docker run -d --name iASIS-KG-Demokritos -v {data}:/usr/local/virtuoso-opensource/share/virtuoso/vad/output -p 11384:8890 -p 1112:1111 asakor/iasis_demokritos:latest
```
