# desarrollo
cd dsia-26-27
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python 1_programacion_avanzada_python/ejemplos/check_entorno.py --strict

# tras crear el repo vacío en GitHub
git clone git@github.com:TU_USUARIO/dsia-26-27-apellido-nombre.git
cd dsia-26-27-apellido-nombre

cp /ruta/a/dsia-26-27/1_programacion_avanzada_python/ejemplos/gitignore_dsia.txt .gitignore

cat > README.md <<'EOF'
# DSIA 2026-2027 — Apellido, Nombre

Máster: ...

## Objetivos
- Aprender Python robusto y testeable
- Automatizar flujos con IA
- Entregar una solución E2E

## Cómo instalar
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt  # cuando exista en tu proyecto
