# Ransomware Simulation

Este proyecto es una simulación de un ransomware básico desarrollado como parte del examen final de la materia de Criptografía en la Universidad del Norte. **Nota: Este proyecto es únicamente con fines educativos. No se debe utilizar para actividades malintencionadas.**

Link del Colab utilizado: https://colab.research.google.com/drive/18G-R4NaEM7OhRZfCMZfA-PolOArRNBct?usp=sharing#scrollTo=JxKdYfuuk3Wu

## Descripción

El ransomware simula los siguientes pasos de operación:

1. **Intercambio de llaves**: Establece una conexión ficticia entre el atacante y la máquina víctima utilizando el protocolo AKE v.2, con certificados digitales y claves RSA de 2048 bits.
2. **Cifrado de archivos**: Cifra archivos de la máquina víctima utilizando una llave derivada del secreto común (KDF) y el cifrador AES en modo CBC.
3. **Notificación de ataque**: Informa a la víctima sobre los archivos cifrados y los pasos a seguir para recuperarlos.
4. **Descifrado de archivos**: Una vez realizado el pago, proporciona instrucciones para recuperar los archivos cifrados.

Además, se incluye una estrategia para verificar la integridad de los archivos afectados.

## Requisitos

- **Lenguaje**: Python (recomendado)
- **Librerías**:
  - `pycryptodome`: para operaciones criptográficas.

## Autores:

- Sebastian Arteta
- Luis Espinel
- German Centanaro
