# JavaStudy
Some exercises about JAVA

1. 正三角形小畫家 triangle NxN
![image](https://github.com/JackShen14/JavaStudy/blob/master/test_jpg/triangle.jpg)


2.創建一個Array 會自動依照i值填入空白。
![image](https://github.com/JackShen14/JavaStudy/blob/master/test_jpg/AutoSpaceArrayList.jpg)

3.樵夫找最快回家路徑 練習題
![image](https://github.com/JackShen14/JavaStudy/blob/master/test_jpg/goHomeFast.jpg)

4.String to date ，再轉換成想要的string 格式
```java
		String tdStartDt = "20191105";  
	  Date date1=new SimpleDateFormat("yyyyMMdd").parse(tdStartDt);
	  String date2 = new SimpleDateFormat("dd/MM/yyyy").format(date1);
	  System.out.println(tdStartDt+"\t"+date1 + "\t" + date2 ); 
	  System.out.println(date1.getClass().getName());
	  System.out.println(date2.getClass().getName());
```








**********************************************   Reference   **********************************************

1.JAVA 字符串格式化 - String.format();  
Reference : https://jax-work-archive.blogspot.com/2015/02/java-stringformat.html  
2.延伸閱讀 - Docker 
摘要: 自動化佈署
URL1: https://docs.microsoft.com/zh-tw/dotnet/architecture/containerized-lifecycle/what-is-docker  
URL2: https://hub.docker.com/search/?q=&type=image  
3.資料  
http://www.bigdatabugs.com/pdf/  
4.


