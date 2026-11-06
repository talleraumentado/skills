# Skills de Taller Aumentado

Skills de Claude Code en español, de **Taller Aumentado** (Profe Rómmel). Las de este catálogo son de cortesía; las más complejas o hechas a la medida de un trabajo se cotizan según su complejidad.

## Skills de cortesía

| Skill | Qué hace |
|---|---|
| `ortografia` | Revisa tildes, puntuación, mayúsculas y tipografía según la RAE, antes de entregar un texto. |
| `gramatica` | Revisa párrafo por párrafo los artículos, la concordancia, los conectores y la claridad. |
| `critica` | Evalúa ideas y trabajos con objetividad, sin darle la razón al usuario por dársela. |

## Cómo instalarlas

Se necesita [Claude Code](https://code.claude.com/docs/en/quickstart.md) y [Git](https://git-scm.com/downloads). Dentro de una sesión de Claude Code, se registra primero el catálogo:

```text
/plugin marketplace add talleraumentado/skills
```

Luego se instala cada skill que se necesite:

```text
/plugin install ortografia@taller-aumentado
```

```text
/plugin install gramatica@taller-aumentado
```

```text
/plugin install critica@taller-aumentado
```

Claude las usa por su cuenta cuando la tarea lo amerita. También se pueden llamar de forma directa, por ejemplo con `/ortografia:ortografia`.

## Cómo actualizarlas

Las actualizaciones no llegan solas. Para actualizar a mano, en la terminal del sistema (no en el chat de Claude Code), se refresca el catálogo y luego se actualiza cada skill instalada (aquí, `ortografia`):

```text
claude plugin marketplace update taller-aumentado
```

```text
claude plugin update ortografia@taller-aumentado
```

La versión nueva se aplica al abrir Claude Code de nuevo.

Para recibirlas de forma automática: `/plugin` → **Marketplaces** → `taller-aumentado` → **Enable auto-update**.

## Skills de pago y a la medida

Si necesita una skill para su propio trabajo, con sus formatos y sus procesos, escríbame con una descripción corta de la tarea. El precio depende de la complejidad y se confirma antes de empezar. La entrega se hace en un repositorio privado, con acceso a las actualizaciones.

## Contacto

- **WhatsApp:** [099 087 8703](https://wa.me/593990878703?text=Hola%2C%20me%20interesa%20una%20skill%20de%20Claude%20Code)
- **Correo:** [talleraumentado593@gmail.com](mailto:talleraumentado593@gmail.com)
