# Datos del Dataset NG-IIoTset

## 📋 Información General

Debido al gran tamaño del dataset completo (~6 GB), los datos principales no están incluidos en este repositorio de GitHub.

## 📁 Obtener el Dataset Completo

### Opción 1: Generar desde PCAP Originales
Si tienes los archivos PCAP originales, puedes regenerar el dataset:

1. Coloca los PCAP en:
   - `data/pcaps/normal/`
   - `data/pcaps/ataques/`

2. Ejecuta el pipeline:
   ```bash
   python src/01_procesar_pcap_con_zeek.py
   jupyter notebook notebooks/NG-IIoTset_Creation.ipynb
