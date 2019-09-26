# alpine_openvpn

Simple Docker container used to ssh into machines behind a OpenVPN server.

Example:

docker run -it --privileged  -v /path/to/your/client.ovpn:/client.ovpn alpine_openvpn:latest

Then you can run ssh inside the container
