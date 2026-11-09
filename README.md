# Salon Appointment Scheduler

Proyecto de freeCodeCamp (Relational Databases): script de Bash con menú para agendar citas en un salón, respaldado por una base de datos PostgreSQL.

- `salon.sql`: volcado de la base (`pg_dump -cC --inserts -U freecodecamp salon`). Se reconstruye con `psql -U postgres < salon.sql`.
- `salon.sh`: muestra los servicios, pide teléfono (registra al cliente si es nuevo) y la hora, y guarda la cita.
