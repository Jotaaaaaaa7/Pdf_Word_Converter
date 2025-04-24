## PDF - WORD - CONVERTER
- Aplicación para convertir archivos de pdf a word y al revés.
- Permite la conversión y descarga tanto individual como por lotes.
- Visualización previa de los PDF.
  
- ⚠ No hay DB, los archivos subidos desaparecen al recargar la web
- ⚠ Para eliminar un archivo hay que 1º darle a X debajo del drag and drop y después darle a eliminar dentro del expander.
  

### Uso en local:

```bash
pip install -r requirements.txt
streamlit run main.py
```

### Docker
```bash
docker compose up --build
```
la app aparece en tu localhost puerto 8501, lo indica en los logs del container
