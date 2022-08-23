##  *** Create Elasticsearch Index and Mapping

![image](https://user-images.githubusercontent.com/111903085/186229927-051c0b78-2e18-4a00-9251-2b6ae94e666c.png)

Run: curl -XPUT "http://20.214.139.173:9200/evcharger?pretty" -d @evcharger_mappings.json -H 'Content-Type:application/json'
![image](https://user-images.githubusercontent.com/111903085/186228654-d55b7ada-0874-4133-8436-a5fb9446efee.png)

==> 에러 때문에 다음 단계으로 못 넘어갔습니다. 그래서 공공데이타의 API를 이용하여 동적으로 Logstash 연동 못했습니다. 

### *** Insert Data in Elasticsearch Using Logstash
![image](https://user-images.githubusercontent.com/111903085/186231578-b6f877e3-f9b8-4aa7-b949-a94c871735cf.png)
![image](https://user-images.githubusercontent.com/111903085/186231899-51ce1e31-a270-4b65-8c27-f798f1fdd8ca.png)

==> jdbc 연결도 에러 나왔습니다
