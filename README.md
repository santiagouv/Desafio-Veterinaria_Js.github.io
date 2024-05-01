## Registrar
Registrar una cita con 

```
node index.js registrar <nombre> <edad> <tipo> <color> <enfermedad>
```

Ejemplo `node index.js registrar Loqui 3 Perro Cafe Mucosidad`

## Leer
Para ver las citas registradas se utiliza

```
node index.js leer
```

Esto visualizara en la terminal las citas como objetos de JavaScript.
Por ejemplo:

```
{
  nombre: 'Loqui',
  edad: '3',
  tipo: 'Perro',
  color: 'Cafe',
  enfermedad: 'Mucosidad'
}
```