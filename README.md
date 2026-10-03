# Comparación de procesamiento paralelo

Proyecto en C# que experimenta con procesamiento secuencial y paralelo mediante Parallel.ForEach y distintos grados máximos de paralelismo.

## Objetivo

Observar cómo cambia el tiempo de procesamiento al ejecutar una misma carga con diferentes niveles de paralelismo.

## Funcionamiento

1. Crea una carga de trabajo.
2. Ejecuta el procesamiento secuencial.
3. Ejecuta la misma carga de forma paralela.
4. Prueba distintos valores de MaxDegreeOfParallelism.
5. Calcula speedup y eficiencia.

## Tecnologías

C#, .NET 8, Task Parallel Library y Stopwatch.

## Métricas

Speedup = tiempo secuencial / tiempo paralelo.

Eficiencia = speedup / cantidad de procesadores.

## Ejecución

Desde la carpeta PruebaProcesador:

dotnet run

## Consideraciones

El resultado depende de la carga, el hardware y el entorno de ejecución.

## Perfil profesional

Proyecto complementario para Software Development y experimentación de rendimiento.
