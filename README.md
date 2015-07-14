# migrar_MaildirToZimbra

El script hace lo siguiente:

* Crea los directorios de usuario en la bandeja Zimbra
* Migra a cada uno de los directorios los correos

### Uso
```ruby
sh maildirtozimbra /export9/mdir/9/47/jpedreros@domain.com/Maildir
``` 
### Tiempos
Casilla 1.2GB, 40.000 correos app.
```ruby
real    32m56.311s
user    6m5.190s
sys     1m23.848s
```
