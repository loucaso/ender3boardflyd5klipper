# Ender 3 – Mellow FLY D5 Klipper Configuration

## 🇬🇧 English

This repository contains configuration files for **Klipper firmware** running on an **Ender 3** 3D printer equipped with a **Mellow FLY D5 mainboard**.

### 🔧 Features and Setup
- **Connection Type:** Configured in **STEP/DIR mode** (⚠️ not UART)
- **Bed Leveling Sensor:** Configured for **CRTouch**
- **Firmware:** Klipper
- **Board:** Mellow FLY D5
- **Printer:** Creality Ender 3

These configuration files are optimized for stable operation using the **default Ender 3 mechanics**, with tuning focused on reliability and ease of setup.

> Note: This setup assumes the stepper drivers are connected via **step/dir pins**. If you are using UART mode, modifications to `printer.cfg` and driver communication parameters will be required.

### 📁 File Structure
/config/
├── printer.cfg
├── mainsail.cfg
├── macros/
└── other custom files

markdown
Copiar código

### ⚙️ Usage
1. Copy the `.cfg` files into your Klipper configuration directory (e.g. `/home/pi/klipper_config/`).
2. Adjust any pin assignments as needed for your specific hardware.
3. Restart the Klipper service to apply changes:
   ```bash
   sudo service klipper restart


Este repositório contém arquivos de configuração para o firmware Klipper, usados em uma impressora Ender 3 com a placa Mellow FLY D5.

🔧 Características e Configuração

Tipo de conexão: Configurado em modo STEP/DIR (⚠️ não UART)

Sensor de nivelamento: Configuração para CRTouch

Firmware: Klipper

Placa: Mellow FLY D5

Impressora: Creality Ender 3

Esses arquivos de configuração foram otimizados para um funcionamento estável com a mecânica original da Ender 3, priorizando confiabilidade e simplicidade na instalação.

Observação: Este setup utiliza drivers em modo STEP/DIR. Se você estiver usando UART, será necessário ajustar o arquivo printer.cfg e os parâmetros de comunicação dos drivers.

📁 Estrutura de Arquivos
/config/
  ├── printer.cfg
  ├── mainsail.cfg
  ├── macros/
  └── outros arquivos personalizados

⚙️ Uso

Copie os arquivos .cfg para o diretório de configuração do Klipper (ex: /home/pi/klipper_config/).

Ajuste os pinos e parâmetros conforme seu hardware.

Reinicie o serviço Klipper para aplicar as mudanças:

sudo service klipper restart

🧠 Credits

Hardware: Mellow FLY D5

Printer: Creality Ender 3

Configurations by: loucaso

   pinout 
   https://mellow-3d.github.io/images/fly-d5/Fly-D5-Pinout.svg

