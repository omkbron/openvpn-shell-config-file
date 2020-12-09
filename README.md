# openvpn-shell-config-file
Shell que ayuda a crear archivos de configuración **OpenVPN** para el cliente

1. Al ejecutar se debe proporcionar el nombre con el cual se generará el archivo con extensión .ovpn.
2. Debe existir la ruta configurada en la variable `KEY_DIR` y dentro de la misma debe exitir los archivos .crt y .key correspondientes.
3. En la variable `OUTPUT_DIR` se debe configurar el directorio en el cual se creará el archivo .ovpn.
4. En la variable  `BASE_CONFIG` se debe configurar el archivo .conf el cual sirve como base para crear el archivo final.

Para mayor referencia revisar el siguiente post: [reference]

[reference]:https://www.digitalocean.com/community/tutorials/como-configurar-un-servidor-de-openvpn-en-ubuntu-18-04-es
