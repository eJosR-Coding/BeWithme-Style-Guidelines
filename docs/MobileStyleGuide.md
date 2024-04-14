
### 3. MobileStyleGuide.md

```markdown
# Mobile Style Guide

## Introducción
Este documento ofrece directrices específicas para el diseño y desarrollo de aplicaciones móviles para Android e iOS en el proyecto BeWithme.

## Plataformas
### Android
- Sigue las Material Design guidelines.
- Usa componentes de Material-UI siempre que sea posible.

### iOS
- Sigue las Human Interface Guidelines.
- Utiliza componentes de UIKit para mantener la consistencia con el ecosistema iOS.

## Interacciones y Gestos
- Asegúrate de que todos los gestos táctiles sean intuitivos y estén documentados en este guía.
- Proporciona feedback visual inmediato para todas las interacciones táctiles.

## Ejemplos de Componentes
### Barra de navegación
- **Android**: Usa `AppBar` con el color primario.
- **iOS**: Usa `NavigationBar` con un botón de retorno claramente visible.

## Código de Ejemplo
```swift
// iOS Navigation Bar
let navBar = UINavigationBar()
navBar.barTintColor = UIColor(named: "PrimaryColor")
navBar.titleTextAttributes = [.foregroundColor: UIColor.white]
