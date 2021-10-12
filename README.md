# ApplicationGatewaySamples

## Recommended alerts
Setup recommended alerts for Application Gateway with <a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpareshverma91%2FApplicationGatewaySamples%2Fmain%2FrecommendedAlerts%2Ftemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>.

We recommend that alerts be setup for:
* Backend failures:
	* Backend sending 5xx.
	* Application Gateway sending 5xx, potentially implying unreachable/unresponsive backend.
	* Non-zero unhealthy backend servers.
* Backend response time/latency degradation
* Application Gateway total time/latency degradation.
* Azure Key Vault access issues for certificates referenced in Application Gateway.
* Insufficient capacity at Application Gateway.
