# ✈️ Caso de Estudio 3: Orquestación Logística Personal (Viajes)

**Escenario:** Estás planeando un viaje de trabajo o vacaciones con múltiples destinos, tienes correos, reservas y PDFs dispersos, el caos mental es total y temes haber cruzado mal alguna fecha.

---

### 📥 1. Los Inputs (El Repositorio de Fuentes)
* `Tickets_Vuelos_Europa.pdf` (5 trayectos diferentes).
* `Reservas_Alojamientos_AirBnb_Hotel.pdf` (Políticas de check-in de 3 lugares).
* `Email_Recomendaciones_Cliente.txt` (Sugerencias de restaurantes).
* `Blog_Horarios_Trenes.txt` (Texto copiado de una web de transporte local).

---

### 🗣️ 2. El Prompt (Usando el Framework FAA)

> **[ANCLAJE]** Cruza absolutamente todas las fuentes de este cuaderno (vuelos, alojamientos, correos y blogs)
>
> **[DIRECTRIZ]** Actúa como mi Asistente Ejecutivo Personal y Agente de Viajes hiper-organizado, tu objetivo es auditar mi logística, armar el itinerario maestro y buscar "puntos de quiebre" (errores en mi planificación)
>
> **[RESTRICCIÓN]**
> - Compara matemáticamente las horas de llegada de mis vuelos con las horas límite de check-in de mis alojamientos en la misma ciudad
> - Si detectas que llego a una ciudad pero no tengo alojamiento reservado esa noche, lanza una 🚨 ALERTA ROJA
> - Integra las recomendaciones de restaurantes solo en los días que físicamente estaré en esa ciudad
>
> **[FORMATO]**
> 1. Lista de "Puntos de Quiebre Logísticos" detectados
> 2. Tabla Cronológica: [Fecha] | [Ciudad] | [Movimiento Logístico] | [Alojamiento] | [Sugerencia de Cena]

---

### 🪄 3. El Output de NotebookLM (La Magia)

#### 🚨 Puntos de Quiebre Logísticos Detectados
* **Conflicto de Check-in (Roma):** Tu vuelo `VY6102` aterriza a las 23:45 (`Tickets_Vuelos`, cita 3). Sin embargo, las reglas del Airbnb en Roma estipulan que no reciben huéspedes después de las 22:00 (`Reservas_Alojamientos`, cita 5). **Necesitas contactar al anfitrión de inmediato.**
* **Hueco Logístico (Día 12):** Tienes el check-out en Milán a las 11:00 am, pero tu siguiente reserva de hotel en Zúrich empieza el Día 13. **Te falta alojamiento para la noche del Día 12.**

#### Itinerario Maestro (Fragmento Saneado)

| Fecha | Ciudad | Movimiento Logístico | Alojamiento | Sugerencia (Base de datos) |
| :--- | :--- | :--- | :--- | :--- |
| 10 Oct | Madrid | Llegada Vuelo IB6650 (14:30) | Hotel Riu Plaza | Cenar en "Casa Lucio" (Recomendado en `Email_Cliente`, cita 1). |
| 11 Oct | Madrid | Libre | Hotel Riu Plaza | N/A |
| 12 Oct | Roma | Vuelo BCN->FCO (Llega 23:45) | Airbnb Trastevere ⚠️ (Ver Alerta) | *Muy tarde para cenar afuera.* |
