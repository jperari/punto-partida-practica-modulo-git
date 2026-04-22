# Diario

## Capturas por tareas

### Tarea 1

![Creación del fork](capturas/1.1._Creación_del_fork.png)
![Fork creado](capturas/1.2._Fork_creado.png)
![Fork clonado](capturas/1.3._Fork_clonado.png)
![Install y run](capturas/1.4._Install_y_run.png)
![App en funcionamiento](capturas/1.5._App_en_funcionamiento.png)
![Captura obligatoria 1 - Remote](capturas/1.6._[Captura_obligatoria_1]_Remote.png)
![Creación de rama dev](capturas/1.7._Creación_rama_dev.png)
![Captura obligatoria 2 - Rama dev en GitHub](capturas/1.8._[Captura_obligatoria_2]_Rama_dev_en_github.png)

### Tarea 2

![Checkout feature-opcion-5](capturas/2.1._Checkout_feature-opcion-5.png)
![Cambios en app.tsx](capturas/2.2._Cambios_en_app.tsx_Opción_5_añadida_y_cambio_3.png)
![Captura obligatoria 3](capturas/2.3._[Captura_obligatoria_3].png)
![Commit y push rama feature-opción-5](capturas/2.4._Commit_y_push_rama_feature-opción-5.png)

### Tarea 3

![Checkout feature-opcion-6](capturas/3.1._Checkout_feature-opcion-6.png)
![Cambios en app.tsx](capturas/3.2._Cambios_en_app.tsx_Opción_6_añadida_y_cambio_3.png)
![Commit y push rama feature-opción-6](capturas/3.3._Commit_y_push_rama_feature-opción-6.png)

### Tarea 4
![Abrir pull request](capturas/4.1._Abrir_pull_request.png)
![Pull request opción 5 antes merge](capturas/4.2._Pull_request_opción_5_antes_merge.png)
![Captura obligatoria 4 - Pestaña files changed](capturas/4.3._[Captura_obligatoria_4]_Pestaña_files_changed.png)
![Merge y commit](capturas/4.4._Merge_y_commit.png)
![Actualiza rama dev local](capturas/4.5._Actualiza_rama_dev_local.png)


### Tarea 5

![Captura obligatoria 5 - PR2 conflicto en GitHub](capturas/5.1._[Captura_obligatoria_5]_PR2_conflicto_en_github.png)
![Captura obligatoria 6 - Resolución de conflicto en VSCode](capturas/5.2._[Captura_obligatoria_6]_Resolución_de_conflicto_en_VSCode.png)
![Captura obligatoria 7 - Apps tras resolución de conflictos](capturas/5.3._[Captura_obligatoria_7]_Apps_tras_resolución_de_conflictos.png)
![Commit y push resolución conflicto en feature-opción-6](capturas/5.4._Commit_y_push_resolución_conflicto_en_feature-opción-6.png)
![PR en GitHub habilitado sin conflictos](capturas/5.5._PR_en_github_habilitado_sin_conflictos.png)
![PR feature-option 6 a dev hecho](capturas/5.6._PR_feature-option_6_a_dev_hecho.png)
![Pull dev en local](capturas/5.7._Pull_dev_en_local.png)

### Tarea 6

![Eliminar ramas en remoto](capturas/6.1._Delete_branches_en_remoto.png)
![Confirmación de rama eliminada](capturas/6.2._Confirmación_de_rama_eliminada.png)
![Captura obligatoria 8 - Eliminación ramas local y comprobación del log](capturas/6.3._[Captura_obligatoria_8]_Eliminación_ramas_local_y_comprobación_del_log.png)

## Capturas obligatorias y preguntas

1. ¿Qué es un fork?

Es una copia de un repositorio de otra persona u organización en tu cuenta de GitHub, se usa para trabajar de forma independiente y puedes o no enviar tus cambios al repositorio original.

![Captura 1](capturas/1.6._[Captura_obligatoria_1]_Remote.png)
![Captura 2](capturas/1.8._[Captura_obligatoria_2]_Rama_dev_en_github.png)

2. ¿Para qué sirve upstream? Para poder actualizar cambios del repo original manteniendo los tuyos

![Captura 3](capturas/2.3._[Captura_obligatoria_3].png)

3. ¿Por qué la rama parte de dev?

main (antes master) no se suele utilizar directamente para desarrollar salvo que el proyecto sea pequeño o personal, lo habitual es crear una rama para desarrollo y por nomenclatura se suele utilizar dev, main se deja así solo para versiones estables.

4. ¿Qué es un conflicto en Git?

Un conflicto se produce cuando dos ramas modifican la misma línea de un fichero, Git no puede decidir automáticamente con qué se queda.

En nuestro caso se produce al haber modificado la línea de description de la opción 3 en dos ramas de forma paralela.

![Captura 4](capturas/4.3._[Captura_obligatoria_4]_Pestaña_files_changed.png)


5. Qué revisaste en la pestaña Files changed y por qué es útil hacerlo antes de mergear

Los cambios que se han hecho en la rama, y es útil para comprobar que la resolución de los conflictos son correctos y no hay nada raro antes de hacer el merge, lo habitual es pasar alguna batería de pruebas justo antes de hacer el merge para estar seguro de que todo funciona correctamente.

![Captura 5](capturas/5.1._[Captura_obligatoria_5]_PR2_conflicto_en_github.png)
![Captura 6](capturas/5.2._[Captura_obligatoria_6]_Resolución_de_conflicto_en_VSCode.png)
![Captura 7](capturas/5.3._[Captura_obligatoria_7]_Apps_tras_resolución_de_conflictos.png)

6. Marcadores <<<<<<< / ======= / >>>>>>>

Separan el código que tienes en la rama donde estás fusionando y los que llegan para poder decidir con cuál nos vamos a quedar.

Elegí la opción que se pedía para la descripción de la opción 3, y el cambio que ya tenía y el nuevo para las opciones 5 y 6 ya que en este caso sí había que agregarlos.

![Captura 8](capturas/6.3._[Captura_obligatoria_8]_Eliminación_ramas_local_y_comprobación_del_log.png)


## Cierre

Ya he trabajado antes con git, también algo, aunque no lo hacíamos mucho, con pull requests (en mi caso con Jira/Atlasian/Bitbucket), y también he hecho bastantes resoluciones de conflictos, no había usando antes un fork aunque si me sonaba el concepto.

