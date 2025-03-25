<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-03-25T10:07:26Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2unveMaGhrMb6dTVApVg3NoaO0M",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2unveMaGhrMb6dTVApVg3NoaO0M"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2unvctsUyelG15kxYLQGfFtse30",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2unvctsUyelG15kxYLQGfFtse30"
				},
				"enabled": true
			},
			"created_at": "2025-03-25T10:07:15Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2unvct0u3ko8HIHQS3P5C5zYvcb",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2unvct0u3ko8HIHQS3P5C5zYvcb"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
