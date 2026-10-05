### Descripción
Renderizador por trazado de rayos de escenas con figuras, con reflejos y refracciones. Paraleliza el procesamiento de píxeles entre múltiples hilos, permitiendo renderizado concurrente escalable. Tecnologías: C++, TBB, CMake

Para ver las imágenes renderizadas, consultar los archivos `ppm` en la carpeta `archivos_config`

### Compilación

```
cmake --preset default
cmake --build --preset gcc-release --parallel
```

### Ejecución
```
./out/build/default/par/Release/render-par \
    render-par/config5.txt \
    render-par/scene5.txt \
    render-par/output.ppm
```
