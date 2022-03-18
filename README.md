# beam-go-Anusha Kanagala

## Instructions to run go on your system
1. Install go from the following link [Go link](/go.dev/learn/)

2. To check the go version use the command :  go version

3. To get Apache Beam Go SDK use the command : go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

4. To install wordcount program use the command : go install github.com/apache/beam/sdks/v2/go/examples/wordcount

5. To run the program use the command : wordcount --input <PATH_TO_INPUT_FILE> --output counts

6. If we get the eror displaying wordcount : command not found 
     -  run the command :  go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
  
