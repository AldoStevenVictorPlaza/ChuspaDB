# Cobertura de Tests

## Estado actual

Se identificaron las siguientes clases con pruebas unitarias en el proyecto:

| Clase probada | Archivo de prueba | Paquete |
| :--- | :--- | :--- |
| `Conexion` | `ConexionTest.java` | `edu.sisinf.estante` |
| `DBConfig` | `DBConfigTest.java` | `edu.sisinf.estante` |
| `ErrorEstante` | `ErrorEstanteTest.java` | `edu.sisinf.estante` |
| `ExportadorCSV` | `ExportadorCSVTest.java` | `edu.sisinf.estante` |
| `ExportadorJSON` | `ExportadorJSONTest.java` | `edu.sisinf.estante` |
| `GeneradorSQL` | `GeneradorSQLTest.java` | `edu.sisinf.estante` |
| `HistorialQuery` | `HistorialQueryTest.java` | `edu.sisinf.estante` |
| `SqlValidator` | `SqlValidatorTest.java` | `edu.sisinf.estante` |


## Observaciones

Para obtener los porcentajes reales de cobertura se requiere generar un reporte JaCoCo mediante:

```bash
mvn test jacoco:report
```

