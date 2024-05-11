# Forking Workflow

El Forking Workflow es un enfoque de colaboración comúnmente utilizado en proyectos de código abierto y equipos distribuidos. Consiste en crear una copia independiente (fork) de un repositorio central y emplear otros flujos de trabajo, como Gitflow o Basic Workflow, en la copia forked para implementar cambios y colaborar en el proyecto.

## Proceso

1. **Fork del Repositorio:** Cada colaborador crea una copia del repositorio central en su cuenta personal de Git, lo que se conoce como "hacer un fork". Esto se realiza en la plataforma de alojamiento del repositorio, como GitHub, GitLab o Bitbucket.

2. **Clonar el Fork:** Una vez que se ha realizado el fork, el colaborador clona su copia del repositorio (fork) en su máquina local utilizando el comando `git clone`.

3. **Implementar Cambios:** El colaborador trabaja en su copia local del repositorio (fork), implementando los cambios necesarios utilizando el flujo de trabajo preferido, como Gitflow o Basic Workflow. Se crean ramas, se realizan commits y se realizan fusiones según sea necesario.

4. **Solicitud de Extracción (Pull Request):** Una vez que los cambios están listos para ser incorporados al repositorio central, el colaborador envía una solicitud de extracción (pull request) desde su fork hacia el repositorio central. Esto notifica a los administradores del proyecto sobre los cambios propuestos y les permite revisar y discutir los cambios antes de fusionarlos en el repositorio principal.

5. **Revisión y Fusión:** Los administradores del proyecto revisan los cambios propuestos en la solicitud de extracción y pueden proporcionar comentarios, sugerencias o solicitar modificaciones adicionales. Una vez que los cambios han sido revisados y aprobados, se fusionan en el repositorio principal.

6. **Actualización del Fork:** Después de que los cambios han sido fusionados en el repositorio principal, el colaborador debe actualizar su copia local del repositorio (fork) para reflejar estos cambios utilizando `git pull`.

## Beneficios

- **Colaboración Distribuida:** Permite a colaboradores de todo el mundo trabajar en paralelo en el mismo proyecto sin necesidad de permisos especiales en el repositorio central.

- **Control de Contribuciones:** Facilita la revisión y discusión de los cambios propuestos antes de ser fusionados en el repositorio central, lo que ayuda a mantener la calidad del código y la integridad del proyecto.

- **Contribuciones Asincrónicas:** Los colaboradores pueden implementar cambios en su propio horario y enviar solicitudes de extracción en cualquier momento, lo que permite una colaboración asincrónica.

## Consideraciones

- **Sincronización:** Es importante mantener actualizado el fork local con los cambios realizados en el repositorio central para evitar conflictos y mantener la consistencia del código.

- **Comunicación:** Se requiere una comunicación efectiva entre los colaboradores y los administradores del proyecto para coordinar los cambios y asegurar una revisión y fusión oportuna de las solicitudes de extracción.

- **Confianza:** Los administradores del proyecto deben confiar en los colaboradores para implementar cambios de manera responsable y seguir las mejores prácticas de desarrollo de software.

