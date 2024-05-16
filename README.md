# CONSULTA 3- CAI 3

```python
## Ejemplo de uso de generar documentos hasheados
archivo_entrada = 'pasajeros_vuelo.txt'
archivo_salida = 'hashes_pasajeros.txt'
generar_hashes(archivo_entrada, archivo_salida)

```python
## Ejemplo de uso para buscar los hashes iguales
archivo1 = 'hashes_delincuentes.txt'
archivo2 = 'hashes_pasajeros.txt'
archivo_salida = 'hashes_comunes.txt'
start_time_total = time.time()
hashes_comunes = busca_comunes(archivo1, archivo2)
guardar_comunes(hashes_comunes, archivo_salida)
end_time_total = time.time()
total_elapsed_time = end_time_total - start_time_total
print(f"Tiempo total de ejecución: {total_elapsed_time:.4f} segundos")
