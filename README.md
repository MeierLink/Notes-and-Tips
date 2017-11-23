# Tips
Tips para desarrollo

<SHELL>
#Carga de archivo configuracion
APP_HOME=/home/user/shell/proyecto_shell
. $APP_HOME/config/config.properties

#Envio de correo
echo "hello world" | mailx -s "subject" someone@somewhere.com

#cat fichero.tar.gz | uuencode fichero.tar.gz | mail -s "subject" correo@dominio.com  // transforma de binario a texto
