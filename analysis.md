# 1. Validar los hash sospechosos
Investigar en ANY.RUN los hash MD5 de la siguiente tabla y completar la información de las columnas 2 y 3

| MD5 Hash | Malicioso / sospechoso / benigno | Nombre de archivo asociado |
|---|---|---|
| 2fd03624e271ec70349ce56fb30f563b | **Malicioso** | **wireframe.exe** |
| c419df63e0121d72411285780c2fc6cc | **No threats detected** | **Benigno** |
| 3acf52e5a62d50bdcedcb89174bf5492 | **No encontrado** | **No encontrado** |
| 766b774626947000e67e0b318f558e94 | **Malicioso** | **gh2st.exe** |
| 422a6ca28a7e4d8e5e498523c6f049f4 | **No encontrado** | **No encontrado** |
| b497845beb135740e6caed03a2020036 | **No encontrado** | **No encontrado** |

# 2. Investigar la actividad maliciosa
En esta parte, utilizaré el sitio web ANY.RUN para investigar el árbol de procesos pertenecientes a cada hash. 

| MD5 Hash | Procesos | 
|---|---|
| 2fd03624e271ec70349ce56fb30f563b | **wireframe.exe, cmd.exe, timeout.exe y NvidiaGPU.exe** |
| c419df63e0121d72411285780c2fc6cc | **Updreg.EXE.exe** |
| 3acf52e5a62d50bdcedcb89174bf5492 | **No encontrado** | 
| 766b774626947000e67e0b318f558e94 | **gh2st.exe, conhost.exe, msedge.exe** | 
| 422a6ca28a7e4d8e5e498523c6f049f4 | **No encontrado** | 
| b497845beb135740e6caed03a2020036 | **No encontrado** | 

# 3. Investigar el informe de texto de actividad maliciosa
En esta parte, utilizaré el sitio web ANY.RUN para obtener el valor SHA256 de cada hash. 

| MD5 Hash | SHA256 | 
|---|---|
| 2fd03624e271ec70349ce56fb30f563b | **9c83a89ea0e56d5af9aa37d2dabed20b2412db8c9694a13128ea173a73557487** |
| c419df63e0121d72411285780c2fc6cc | **f47f854d327c589d174d3bb5b55d5c05f5aca73df52a6bef47596b9010190291** |
| 3acf52e5a62d50bdcedcb89174bf5492 | **No encontrado** | 
| 766b774626947000e67e0b318f558e94 | **88dd2037d0c43abacebad866df3f8ccd2ee7d64b01405aa6756a3a1c2fac28fa** | 
| 422a6ca28a7e4d8e5e498523c6f049f4 | **No encontrado** | 
| b497845beb135740e6caed03a2020036 | **No encontrado** | 


# 4. Investigar el gráfico de procesos de actividad maliciosa
En esta parte, utilizaré el sitio web ANY.RUN para obtener el valor SHA256 de cada hash. 

| MD5 Hash | SHA256 | 
|---|---|
| 2fd03624e271ec70349ce56fb30f563b | **9c83a89ea0e56d5af9aa37d2dabed20b2412db8c9694a13128ea173a73557487** |
| c419df63e0121d72411285780c2fc6cc | **f47f854d327c589d174d3bb5b55d5c05f5aca73df52a6bef47596b9010190291** |
| 3acf52e5a62d50bdcedcb89174bf5492 | **No encontrado** | 
| 766b774626947000e67e0b318f558e94 | **88dd2037d0c43abacebad866df3f8ccd2ee7d64b01405aa6756a3a1c2fac28fa** | 
| 422a6ca28a7e4d8e5e498523c6f049f4 | **No encontrado** | 
| b497845beb135740e6caed03a2020036 | **No encontrado** | 
