# CliniVet
## Ejercicio integrador C# POO

### Requerimiento
Se quiere diseñar un sistema informático básico utilizando ventanas que permita llevar la administración de una clínica veterinaria. Se debe tener en cuenta que la clínica está destinada a atender esencialmente Perros y Gatos, pero que se está extendiendo para atender aves.

Se quiere que el mencionado sistema maneje los datos vinculados a Clientes, Servicios y Mascotas, donde no se dificulte obtener algunos balances.

De los clientes queremos conservar: nombre, apellido, edad, número de identificación y el historial de servicios, este último definido por un código de operación y el monto pagado.

Los servicios son escencialmente los siguientes:
- **Consulta:** $10.000 * Tipo
- **Spa:** $1.500 * Kilo
- **Limpieza Dental**: $10.000
- **Intervención Quirúrgica:** Por definir

El tipo específicado en la tabla tiene la intención de que se pueda establecer más adelante un precio más alto para las aves.

De las mascotas debe guardarse: el código de operación el cual debe estar relacionado con el código del cliente, peso, nombre, fecha y diagnóstico.

Esta información debe poder permitir hacer consultas sobre:
- Cantidad de dinero recaudado en una fecha.
- Total recaudado por un cliente dado.
- Listar las mascotas de un cliente dado.
- Listar los perros por raza.
- Listar todos los clientes.
- Listar las consultas por un rango de fecha, indicando la mascota y el cliente respectivo
