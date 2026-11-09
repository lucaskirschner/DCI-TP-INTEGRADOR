# USB3_ETH_Board

Trabajo práctico final de la asignatura **Diseño de Circuitos Impresos (DCI)** de la **Carrera de Especialización en Sistemas Embebidos** de la Facultad de Ingeniería de la Universidad de Buenos Aires (FIUBA).

- **Autor:** Ing. Lucas Kirschner
- **Título:** Adaptador USB 3.1 a Gigabit Ethernet
- **Cursada:** OCT-NOV-DIC 2026

## Descripción

**USB3_ETH_Board** es una placa adaptadora que permite implementar una interfaz de red **Gigabit Ethernet** a partir de una conexión **USB 3.1**, utilizando el controlador **LAN7800**.

El objetivo del trabajo es desarrollar una placa de circuito impreso multicapa que integre interfaces de alta velocidad USB y Gigabit Ethernet, aplicando criterios de diseño relacionados con la integridad de señal, impedancia controlada, ruteo de pares diferenciales, continuidad de los caminos de retorno, distribución de alimentación y compatibilidad electromagnética.

El diseño se desarrolla sobre una **PCB de 4 capas** utilizando **KiCad**.

## Estructura del repositorio

```text
USB3_ETH_Board/
├── doc/
│   └── propuesta/
│       └── README.md
├── info/
├── pcb/
├── .gitignore
├── LICENSE
└── README.md
```

### `doc/`

Documentación elaborada durante el proyecto, incluyendo la propuesta del trabajo, notas de ingeniería, cálculos, criterios de diseño, análisis y documentación complementaria.

La propuesta del trabajo se encuentra en [`doc/propuesta/README.md`](doc/propuesta/README.md).

### `info/`

Documentación externa utilizada como referencia durante el desarrollo, principalmente hojas de datos de componentes relevantes y notas de aplicación.

### `pcb/`

Archivos de diseño electrónico desarrollados en KiCad, incluyendo esquemático, diseño de PCB, bibliotecas particulares, modelos 3D y archivos de fabricación generados.

## Licencia

Este proyecto se distribuye como **hardware abierto** bajo la **CERN Open Hardware Licence Version 2 – Strongly Reciprocal (CERN-OHL-S-2.0)**.

Los términos completos de la licencia deben incluirse en el archivo [`LICENSE`](LICENSE) del directorio raíz del repositorio.
