# Pruebas_Unitarias_Sistema_Registro
Documento de pruebas unitarias del sistema de registro
README.md Descriptivo
Copiar
# Pruebas Unitarias - Sistema de Registro de Usuarios

## Descripción
Este repositorio contiene la documentación de pruebas unitarias para el sistema de registro de usuarios.

## Contenido
- `/Pruebas/` - Documentos de pruebas unitarias
- `/Documentacion/` - Documentación adicional

## Autor
[Tu nombre]

## Fecha
Noviembre 2025
4. Usar Ramas para Cambios Importantes
Copiar
# Crear rama para nuevas pruebas
git checkout -b agregar-nuevas-pruebas

# Hacer cambios y commit
git add .
git commit -m "Agregar 5 nuevos casos de prueba"

# Volver a main y fusionar
git checkout main
git merge agregar-nuevas-pruebas
SOLUCIÓN DE PROBLEMAS COMUNES
Error: "Permission denied"
Copiar
# Verificar credenciales
git config --global user.name
git config --global user.email

# Usar token de acceso personal en lugar de contraseña
# Ir a GitHub → Settings → Developer settings → Personal access tokens
Error: "Repository not found"
Copiar
# Verificar URL remota
git remote -v

# Actualizar URL si es necesario
git remote set-url origin https://github.com/usuario/repo.git
Deshacer último commit (sin perder cambios)
Copiar
git reset --soft HEAD~1
Deshacer cambios en un archivo
Copiar
git checkout -- nombre_archivo.docx
RECURSOS ADICIONALES
Documentación oficial de Git: https://git-scm.com/doc
Guías de GitHub: https://guides.github.com
Tutorial interactivo: https://learngitbranching.js.org
Cheat Sheet de Git: https://education.github.com/git-cheat-sheet-education.pdf
