# Recordatorios y recetas Linux para la mala memoria.

### Activar las teclas de función por defecto en teclados Mac.
```bash
echo 0 | sudo tee /sys/module/hid_a
```

### Arreglo cuando se pierde el teclado y el ratón.
Ejecutar desde shell remoto y reiniciar.
```bash
sudo apt install xserver-xorg-input-all
```

### Información general, pero importante, del sistema.
```bash
neofetch
```

### Información de la distribución base.
```bash
cat /etc/upstream-release/lsb-release
```

### Información de la distribución propia.
```bash
cat /etc/lsb-release

cat /etc/linuxmint/info            # fichero propio de Linux Mint
```

### Versión e Info extendida con el logo de la distribución
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

### Monitorización del sistema (procesos, cpu's, temp's, etc)
```bash
glances
```

### Fecha de instalación del sistema.
```bash
ll -d /lost+found
```
La fecha de este directorio es la fecha de instación.
