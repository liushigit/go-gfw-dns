# myDns

可以按照gfwlist来选择是否使用国内的dns还是国外的dns

````
ListenAndServe(
		"0.0.0.0:53",
		[]string{"114.114.114.114:53"},
		[]string{"114.114.114.114:53", "106.187.35.20:53"})
````    
