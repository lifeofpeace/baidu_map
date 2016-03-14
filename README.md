###百度地图API 判断点击的是地图还是覆盖物

```js
map.addEventListener("click", function(e){ 
	if(e.overlay){
	    alert('您点击的是覆盖物：'+e.overlay.toString());   
	}else{
	    alert('您点击的是地图');
	}						    
})
```

演示地址：http://itmyhome.com/baidu_map