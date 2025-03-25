<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"bindings": ["public"],
	"created_at": "2025-03-25T10:07:20Z",
	"description": "sample cloud endpoint",
	"domain": {
		"id": "rd_2unvcz4J3xGmilA7EJJvbyy0NEF",
		"uri": "https://api.ngrok.com/reserved_domains/rd_2unvcz4J3xGmilA7EJJvbyy0NEF"
	},
	"hostport": "endpoint-example2.com:443",
	"id": "ep_2unvdZ3T4zwqFSubhBW2bLZzsdI",
	"metadata": "{\"environment\": \"staging\"}",
	"pooling_enabled": false,
	"proto": "https",
	"public_url": "https://endpoint-example2.com",
	"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
	"type": "cloud",
	"updated_at": "2025-03-25T10:07:20Z",
	"uri": "https://api.ngrok.com/endpoints/ep_2unvdZ3T4zwqFSubhBW2bLZzsdI",
	"url": "https://endpoint-example2.com"
}
```
