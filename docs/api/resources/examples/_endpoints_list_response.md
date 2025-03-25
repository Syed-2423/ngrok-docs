<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
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
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-25T10:07:18Z",
			"hostport": "517ac31a65af.ngrok.paid:443",
			"id": "ep_2unvdKBovvBWrwXpl55sTW8y6bj",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2unvau3d5Fk5Xc7khbxyoIuTju8",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://517ac31a65af.ngrok.paid",
			"tunnel": {
				"id": "tn_2unvdKBovvBWrwXpl55sTW8y6bj",
				"uri": "https://api.ngrok.com/tunnels/tn_2unvdKBovvBWrwXpl55sTW8y6bj"
			},
			"tunnel_session": {
				"id": "ts_2unvdB475aG9xc3GwKc6WjW1SdQ",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2unvdB475aG9xc3GwKc6WjW1SdQ"
			},
			"type": "ephemeral",
			"updated_at": "2025-03-25T10:07:18Z",
			"upstream_url": "http://localhost:80",
			"url": "https://517ac31a65af.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-03-25T10:07:16Z",
			"domain": {
				"id": "rd_2unvcz4J3xGmilA7EJJvbyy0NEF",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2unvcz4J3xGmilA7EJJvbyy0NEF"
			},
			"edge": {
				"id": "edgtls_2unvct0u3ko8HIHQS3P5C5zYvcb",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2unvct0u3ko8HIHQS3P5C5zYvcb"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2unvcxlqc3Lvp7Mq91JbLgELTay",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-03-25T10:07:16Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
