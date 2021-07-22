# hugegraph-hbase-endpoint
resolve dependency conflict on "hugegraph" and "hbase-endpoint"

"Hugegraph" need "protobuf" 3.x version, but "hbase-endpoint" 2.x version need "protobuf" 2.x, so we create this project to resolve the problem by use shade; 
