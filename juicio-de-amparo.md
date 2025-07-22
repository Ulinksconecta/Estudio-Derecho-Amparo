# Proceso de Juicio de Amparo

## Diagrama de Flujo

```mermaid
graph TD
    A[Inicio: Violación de un derecho humano<br>Ejemplo: Detención arbitraria de María] --> B[Identificar la violación<br>Art. 16 Constitucional: Libertad personal]
    B --> C[Redactar demanda de amparo<br>- Nombre de la quejosa<br>- Autoridad responsable<br>- Acto reclamado<br>- Derecho violado<br>- Pruebas]
    C --> D[Presentar demanda<br>Juzgado de Distrito en Oaxaca<br>Art. 108 Ley de Amparo]
    D --> E{Juez revisa la demanda<br>24-48 horas, Art. 114 Ley de Amparo}
    E -->|Cumple requisitos| F[Demanda admitida]
    E -->|No cumple requisitos| G[Demanda desechada<br>Fin del proceso]
    F --> H[Solicitar suspensión<br>Evitar daños mientras se resuelve<br>Art. 124 Ley de Amparo]
    H --> I[Audiencia constitucional<br>- Presentar argumentos<br>- Revisar pruebas]
    I --> J{Juez emite sentencia}
    J -->|Amparo concedido| K[Se declara nula la detención<br>- Ordena no repetición<br>- Posible reparación del daño]
    J -->|Amparo negado| L[Fin del proceso<br>Posible apelación]
    K --> M[Autoridad debe cumplir<br>Art. 192 Ley de Amparo]
    M -->|Cumple| N[Fin: Derecho protegido]
    M -->|No cumple| O[Denunciar incumplimiento<br>al juez]
    O --> N
