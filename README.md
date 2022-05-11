### Activar las teclas de función por defecto en teclados Mac.
```bash
echo 0 | sudo tee /sys/module/hid_a
```

### Arreglo cuando se pierde el teclado y el ratón.
Ejecutar desde shell remoto y reiniciar.
```bash
sudo apt install xserver-xorg-input-all
```

### Información general, pero importante del sistema.
```bash
neofetch
```

### Configuración de la fecha y hora.
```bash
timedatectl
```

### Información del uso de DNS.
```bash
systemd-resolve --status
```
La utilidad en si misma provee mucha funcionalidad para investigar DNS.
