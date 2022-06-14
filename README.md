# forticlient-vpn-client-k8s

kubectl create secret generic vpn-secret \
	--from-file=vpn_credential.pfx=vpn_credential.pfx \
	--from-literal=PFX_PASSWORD="pfx password here" \
	--from-literal=VPN_ADDRESS="vpn address here" \
	--from-literal=VPN_USERNAME="vpn user name" \
	--from-literal=VPN_PASSWORD="vpn password"
