# Practica1PPC
Simulación de sistema hospitalario automatizado con paradigmas concurrente, paralelo y asíncrono.
Se utilizan los siguientes paradigmas:
Concurrente: Simula múltiples pacientes llegando y registrándose en recepción en paralelo, controlados con semáforos para reflejar plazas limitadas.
Paralelo: Realiza el cómputo de diagnóstico (simulación de riesgo) en procesos separados para aprovechar múltiples núcleos y reducir latencia.
Asíncrono: Gestiona colas de pacientes por prioridad (grave/crítico vs. leve/moderado), asegurando que los casos urgentes se atienden primero.
