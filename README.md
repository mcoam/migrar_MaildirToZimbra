# migrar_MaildirToZimbra

El script hace lo siguiente:

* Crea los directorios de usuario en la bandeja Zimbra
* Migra a cada uno de los directorios los correos

### Uso
```ruby
sh maildirtozimbra /export9/mdir/9/47/jpedreros@domain.com/Maildir
``` 
### Tiempos
Casilla 1GB, 35.000 correos app.
```ruby
real	39m29.042s
user	5m23.760s
sys	1m38.153s
```
