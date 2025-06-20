# Aula compartida
Infraestructura de un aula compartida por cursos y alumnos distintos vía NFS. Usando NIS o LDAP

## Aula de informática de libre acceso – Propuesta

- [📄 Resumen](resumen.pdf)
- [📄 Aula informática](aula_informatica.pdf)
- [📄 Aula informática con LDAP](aula_informatica_ldap.pdf)
- [📄 Congelar sistema](congelar_sistema.pdf)
- [📄 Cuotas](cuotas.pdf)

Los documentos proporcionados describen la configuración de un aula informática centralizada mediante diversas tecnologías. 

Se detalla la implementación de un servidor de información (NIS o LDAP) para gestionar usuarios y grupos de manera unificada, junto con un servidor NFS para compartir los directorios personales de los estudiantes. 

Las máquinas cliente se configuran para acceder a estos recursos, utilizando Autofs para montar directorios de forma dinámica y PAM para la creación automática de directorios locales. 

Además, se explora el uso de cuotas de disco para limitar el espacio de los usuarios y la aplicación de Bilibop-lockfs para congelar el sistema operativo de los clientes, asegurando su consistencia y facilitando las actualizaciones mediante scripts automatizados.
