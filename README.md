# Comandos-Linux



/sbin/reboot
/sbin/shutdonw

## Información del sistema

    arch: mostrar la arquitectura de la máquina (1).
    uname -m: mostrar la arquitectura de la máquina (2).
    uname -r: mostrar la versión del kernel usado.
    dmidecode -q: mostrar los componentes (hardware) del sistema.
    hdparm -i /dev/hda: mostrar las características de un disco duro.
    hdparm -tT /dev/sda: realizar prueba de lectura en un disco duro.
    cat /proc/cpuinfo: mostrar información de la CPU.
    cat /proc/interrupts: mostrar las interrupciones.
    cat /proc/meminfo: verificar el uso de memoria.
    cat /proc/swaps: mostrar ficheros swap.
    cat /proc/version: mostrar la versión del kernel.
    cat /proc/net/dev: mostrar adaptadores de red y estadísticas.
    cat /proc/mounts: mostrar el sistema de ficheros montado.
    lspci -tv: mostrar los dispositivos PCI.
    lsusb -tv: mostrar los dispositivos USB.
    date: mostrar la fecha del sistema.
    cal 2011: mostrar el almanaque de 2011.
    cal 07 2011: mostrar el almanaque para el mes julio de 2011.
    date 041217002011.00: colocar (declarar, ajustar) fecha y hora.
    clock -w: guardar los cambios de fecha en la BIOS.

## Apagar (Reiniciar Sistema o Cerrar Sesión)

    shutdown -h now: apagar el sistema (1).
    init 0: apagar el sistema (2).
    telinit 0: apagar el sistema (3).
    halt: apagar el sistema (4).
    shutdown -h hours:minutes &: apagado planificado del sistema.
    shutdown -c: cancelar un apagado planificado del sistema.
    shutdown -r now: reiniciar (1).
    reboot: reiniciar (2).
    logout: cerrar sesión.
