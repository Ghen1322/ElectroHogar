# ElectroHogar
Objetivos de la Red
Garantizar conectividad segura y eficiente entre los departamentos de ElectroHogar.

Facilitar la comunicación interna y el acceso a recursos compartidos (servidores, bases de datos).

Implementar seguridad perimetral para proteger datos sensibles (clientes, pagos, inventario).

Escalar la infraestructura para soportar crecimiento futuro (nuevas tiendas en línea, IoT).

🏢 Departamentos Incluidos
Departamento	Función Principal	Servicios Clave
🔧 Desarrollo	Mantenimiento de la plataforma web y apps.	Git, Jenkins, Docker
🛠️ Soporte TI	Resolución de incidencias y asistencia.	Zabbix, VPN, HelpDesk
📊 Administración	Gestión financiera y RRHH.	ERP, SharePoint
🌐 Asignación de IP y Subredes
Estructura basada en VLANs para segmentación de red:

Subred	Rango IP	VLAN	Departamento	Uso
192.168.1.0/24	192.168.1.1 - 192.168.1.50	10	Desarrollo	Servidores, GitLab
192.168.2.0/24	192.168.2.1 - 192.168.2.50	20	Soporte TI	Monitoreo, VPN
192.168.3.0/24	192.168.3.1 - 192.168.3.50	30	Administración	ERP, Correo
192.168.4.0/24	192.168.4.1 - 192.168.4.10	40	Dispositivos IoT	Smart Inventory
Gateway predeterminado: 192.168.X.1 (por subred)
DNS Interno: 192.168.1.10 (Servidor local).

👥 Roles y Responsabilidades
Rol	Responsabilidades	Departamento
Administrador de Red	Configuración de switches, firewall y VLANs.	Soporte TI
DevOps	Automatización y despliegues seguros.	Desarrollo
Soporte N1/N2	Resolución de tickets y mantenimiento.	Soporte TI
Analista de Seguridad	Auditorías y cumplimiento ISO 27001.	Administración
