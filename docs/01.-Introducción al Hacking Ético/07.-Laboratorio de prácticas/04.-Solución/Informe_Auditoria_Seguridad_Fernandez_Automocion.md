
# Informe de Auditoría de Seguridad - Fernández Automoción

## Introducción

Este informe documenta las vulnerabilidades identificadas durante la auditoría de seguridad realizada en Fernández Automoción. Cada vulnerabilidad se ha analizado en detalle, incluyendo la valoración CVSS (Common Vulnerability Scoring System), los vectores de ataque, los impactos y las recomendaciones para su mitigación.

## Vulnerabilidades Identificadas

### 1. Vulnerabilidad en el sistema de correo de la compañía

- **Descripción**: Existe una vulnerabilidad crítica en el servidor de correo expuesto a internet, que permite tomar el control del mismo y acceder a los mensajes de cualquier usuario. Además, permite suplantar la identidad de los usuarios al enviar correos electrónicos en su nombre. Existe un exploit público accesible desde exploit-db y un parche oficial del fabricante.
  
- **Valoración CVSS**:
  - **Base Metrics**:
    - **Attack Vector (AV)**: Network (N)
    - **Attack Complexity (AC)**: Low (L)
    - **Privileges Required (PR)**: None (N)
    - **User Interaction (UI)**: None (N)
    - **Scope (S)**: Changed (C)
    - **Confidentiality Impact (C)**: High (H)
    - **Integrity Impact (I)**: High (H)
    - **Availability Impact (A)**: High (H)
  - **Temporal Metrics**:
    - **Exploit Code Maturity (E)**: High (H)
    - **Remediation Level (RL)**: Official Fix (O)
    - **Report Confidence (RC)**: Confirmed (C)
  
- **Vector CVSS**: `CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H/E:H/RL:O/RC:C`

- **Justificación**:
  - Esta vulnerabilidad afecta al servidor de correo, comprometiendo su seguridad de manera crítica. Permite acceder a información confidencial y afecta la integridad y disponibilidad del sistema.

---

### 2. Vulnerabilidad de Inyección SQL en el servidor web

- **Descripción**: Se ha detectado una vulnerabilidad de inyección SQL en el servidor web expuesto a internet. Esta permite consultar datos de otras bases de datos, incluida la base de datos de contabilidad. Para acceder a la funcionalidad vulnerable, se requiere un usuario autenticado de bajo privilegio. La vulnerabilidad es desconocida públicamente y fue descubierta por el auditor.

- **Valoración CVSS**:
  - **Base Metrics**:
    - **Attack Vector (AV)**: Network (N)
    - **Attack Complexity (AC)**: Low (L)
    - **Privileges Required (PR)**: Low (L)
    - **User Interaction (UI)**: None (N)
    - **Scope (S)**: Unchanged (U)
    - **Confidentiality Impact (C)**: High (H)
    - **Integrity Impact (I)**: Low (L)
    - **Availability Impact (A)**: None (N)
  - **Temporal Metrics**:
    - **Exploit Code Maturity (E)**: Proof-of-Concept (P)
    - **Remediation Level (RL)**: Unavailable (U)
    - **Report Confidence (RC)**: Confirmed (C)

- **Vector CVSS**: `CVSS:3.1/AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:L/A:N/E:P/RL:U/RC:C`

- **Justificación**:
  - Esta vulnerabilidad afecta al servidor web, exponiendo datos confidenciales sin modificar o afectar la disponibilidad. La valoración refleja su criticidad en términos de confidencialidad.

---

### 3. Vulnerabilidad de Ejecución Remota de Código en servidor FTP interno

- **Descripción**: Se detectó una vulnerabilidad en el servidor FTP interno que permite la ejecución remota de código con privilegios del sistema. Este acceso también permite entrar a una subred de administración restringida. Existe un parche público, pero el auditor tuvo que modificar una prueba de concepto para explotar esta vulnerabilidad.

- **Valoración CVSS**:
  - **Base Metrics**:
    - **Attack Vector (AV)**: Adjacent Network (A)
    - **Attack Complexity (AC)**: High (H)
    - **Privileges Required (PR)**: None (N)
    - **User Interaction (UI)**: None (N)
    - **Scope (S)**: Changed (C)
    - **Confidentiality Impact (C)**: High (H)
    - **Integrity Impact (I)**: High (H)
    - **Availability Impact (A)**: High (H)
  - **Temporal Metrics**:
    - **Exploit Code Maturity (E)**: Proof-of-Concept (P)
    - **Remediation Level (RL)**: Official Fix (O)
    - **Report Confidence (RC)**: Confirmed (C)

- **Vector CVSS**: `CVSS:3.1/AV:A/AC:H/PR:N/UI:N/S:C/C:H/I:H/A:H/E:P/RL:O/RC:C`

- **Justificación**:
  - Esta vulnerabilidad compromete la seguridad del servidor FTP interno y permite el acceso a la subred de administración. Debido a su criticidad, es esencial aplicar el parche disponible para mitigarlo.

## Conclusión

Las vulnerabilidades encontradas presentan un riesgo significativo para la seguridad de Fernández Automoción. Es fundamental priorizar la mitigación de estas vulnerabilidades, especialmente en el sistema de correo y el servidor FTP interno, para evitar potenciales ataques y compromisos de información confidencial. Se recomienda implementar los parches propuestos y realizar una monitorización continua de estos sistemas para asegurar su protección.
