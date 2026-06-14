# references-backup

Personal backup of forked repositories and reference materials for learning and study.
Organized by topic for easy navigation and offline access.

---

## 📦 Contents by Category

### 🔤 JavaScript

| Repository | Original | Description |
|------------|----------|-------------|
| **33-js-conceptos** | [33-js-concepts](https://github.com/leonardomso/33-js-conceptos) | Conceptos esenciales de JavaScript |
| **clean-code-javascript-es** | [clean-code-javascript](https://github.com/andersontr15/clean-code-javascript-es) | Mejores prácticas de código limpio (español) |
| **You-Dont-Know-JS** | [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) | Guía profunda y exhaustiva de JavaScript |
| **javascript-algorithms** | [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) | Algoritmos y estructuras de datos en JavaScript |

### 📚 Resources & Books

| Repository | Original | Description |
|------------|----------|-------------|
| **libros-programacion-gratis** | [libros-programacion-gratis](https://github.com/midudev/libros-programacion-gratis) | Colección de libros de programación gratis |

### 🎨 Design Patterns

Patrones de diseño en JavaScript y arquitectura.

### 🗄️ SQL & Databases

Recursos SQL, PostgreSQL, y patrones de base de datos.

### 🌐 Web Development

HTML, CSS, frontend frameworks, y mejores prácticas web.

### 📌 Other

Recursos adicionales y referencias variadas.

---

## 📝 Purpose

These are forked repositories cloned as backup and reference material for:
- Learning and studying programming concepts
- Quick reference during development
- Offline access to important resources
- Personal knowledge base for technical education

**Note:** These folders are NOT Git repositories. Each is a copy of the original without version history.

---

## 🔄 To Update References

To refresh any reference with the latest version from the original repository:

```bash
# Example: Update 33-js-conceptos
REPO_URL="https://github.com/leonardomso/33-js-conceptos.git"
DEST_PATH="javascript/33-js-conceptos"

git clone "$REPO_URL" /tmp/update
rm -rf "$DEST_PATH"
cp -r /tmp/update "$DEST_PATH"
rm -rf /tmp/update
cd ~/references-backup
git add .
git commit -m "chore: update $DEST_PATH"
git push
```

---

## 🔗 Original Repositories

Quick access to the original projects:

**JavaScript & Algorithms**
- [leonardomso/33-js-conceptos](https://github.com/leonardomso/33-js-conceptos)
- [andersontr15/clean-code-javascript-es](https://github.com/andersontr15/clean-code-javascript-es)
- [getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)
- [trekhleb/javascript-algorithms](https://github.com/trekhleb/javascript-algorithms)

**Books & Resources**
- [midudev/libros-programacion-gratis](https://github.com/midudev/libros-programacion-gratis)

---

## 🎯 Learning Areas Covered

- **JavaScript**: Core concepts, clean code, algorithms, advanced patterns
- **Books**: Free programming books and resources in Spanish
- **Design Patterns**: Architecture and design principles
- **SQL & Databases**: Database design and optimization
- **Web Development**: Frontend best practices and frameworks

---

*Last synced: 2026-06-14*
*Personal learning backup | All references are for educational purposes*
