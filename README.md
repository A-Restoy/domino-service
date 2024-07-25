# domino-service
# Script run server domino

# Añadimos el fichero domino-service en /etc/systemd/system/
add file domino.service in /ect/systemd/system/  

# Reacargamos el daemos systemctl para que reconozca el nuevo servicio añadido
systemctl daemon-reload   

# Habilitar servicios para que se inicie domino si se reinicia el servidor linux
systemctl enable domino.service   

# Reiniciar servidor domino
systemctl restart domino.service   


