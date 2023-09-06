### User
- id
- name?
- email?
- rut?
- birthDate?
- phone
- adress
- comuna
- role
- enfCronica
- emailVerified
- accounts
- sessions

### Clase
- id
- Taller
- Profesor user[]
- Fecha
- Asistecia user[]
- realizada
- suspendida
- reagendada

### Taller
- id
- name
- Profesor[]
- participantes[]


### Role
- id
- name (Participante, Socio, Profesor, Delegado, Directiva, Administrador)

### PagoCuotaMensual
- id
- fechaRealizado
- Monto
- Meses Pagados
- user


