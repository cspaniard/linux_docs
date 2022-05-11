### Activar las teclas de función por defecto en teclados Mac.
```bash
echo 0 | sudo tee /sys/module/hid_a
```

### Arreglo cuando se pierde el teclado y el ratón.
Ejecutar desde shell remoto y reiniciar.
```bash
sudo apt install xserver-xorg-input-all
```

