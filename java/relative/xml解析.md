# **xml解析**

## 1.使用org.json包来解析xml字符串

	import org.json.JSONException;
	import org.json.JSONObject;
	import org.json.XML;
	public class JsonUtils {  
	     public static String xml2jsonString(String xml)throws JSONException{  
	     JSONObject xmlJSONObj = XML.toJSONObject(xml);  
	     return xmlJSONObj.toString();  
	     }  
	}

## 2.sax解析  
- [ ] 未完成事项

## 3.dom解析  
- [ ] 未完成事项