Spring-cloud-config 读取配置文件的先后顺序是:
1. lab-3-client.yml
2. lab-3-client.properties
3. lab-3-client-northamerica.yml
4. lab-3-client-northamerica.properties

最后的配置的值由最后读到的文件决定。