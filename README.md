# Sincronizar_dependências
uv run sync
# Compilar com Nuitka

uv run python -m nuitka --onefile --follow-imports --enable-plugin=tk-inter --include-data-dir=./Quizzino=Quizzino --output-dir=dist main.py

# Verificar o executável
ls -la dist/

python -m py_compile main.py
