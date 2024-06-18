# Trabajo Fin de Grado - Criptosistemas Avanzados de Clave Pública

Este trabajo está organizado en tres directorios principales, cada uno de los cuales corresponde a un criptosistema distinto: McEliece, Merkle-Hellman y NTRU. A continuación, se describe la estructura de cada uno de estos directorios y los archivos que contienen.

## Directorios y Archivos

### 1. McEliece

- **Archivo:** `McEliece.ipynb`
- **Descripción:** Este archivo Jupyter Notebook implementa el criptosistema de McEliece. El criptosistema de McEliece es un esquema de cifrado asimétrico basado en códigos líneales, más concretamente en códigos Goppa binarios. Este Notebook cubre la generación de claves, el proceso de cifrado y descifrado, así como ejemplos prácticos y pruebas del funcionamiento del sistema.

### 2. Merkle-Hellman

- **Archivo:** `Merkle-Hellman.ipynb`
  - **Descripción:** Este archivo Jupyter Notebook implementa el criptosistema de Merkle-Hellman. El criptosistema de Merkle-Hellman es un esquema de cifrado asimétrico basado en el problema de la mochila, específicamente en el problema de la suma de subconjuntos (Subset Sum Problem). El Notebook incluye la generación de claves, el cifrado y descifrado, y ejemplos de uso.

- **Archivo:** `LowDensityAttack.ipynb`
  - **Descripción:** Este archivo implementa el ataque de baja densidad de Lagarias-Odlyzko, enfocándose en resolver el problema de la suma de subconjuntos.

- **Archivo:** `BrokenMH.ipynb`
  - **Descripción:** Este archivo integra el ataque de baja densidad con el criptosistema Merkle-Hellman, mostrando cómo se puede romper el criptosistema. A partir de un mensaje encriptado con Merkle-Hellman, el Notebook describe el proceso para obtener el mensaje original, demostrando la efectividad del ataque.

### 3. NTRU

- **Archivo:** `NTRU.ipynb`
  - **Descripción:** Este archivo Jupyter Notebook implementa el criptosistema NTRU. NTRU es un criptosistema basado en la teoría de retículos y en anillos polinómicos convolucionales, ofreciendo una alternativa eficiente a otros sistemas criptográficos. El Notebook incluye la generación de claves, el cifrado y descifrado, y ejemplos de uso práctico.
