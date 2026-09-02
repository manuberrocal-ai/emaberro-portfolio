# Ruleset recomendado para `main`

- impedir borrado y actualización forzada de `main`;
- exigir pull request antes de fusionar;
- exigir una aprobación y resolver conversaciones;
- bloquear la fusión si hay conflictos;
- añadir checks obligatorios solo después de crear y observar una CI estable;
- limitar excepciones al propietario y documentar su uso.

Activar secret scanning y push protection. Si se incorporan dependencias o GitHub Actions, añadir Dependabot y code scanning.
