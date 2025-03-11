# Interface de Connexion iOS Minimaliste

Une interface de connexion élégante et minimaliste pour applications iOS, développée avec SwiftUI. Cette interface propose un design épuré et moderne, parfaitement adapté aux applications professionnelles.

<img width="349" alt="SCR-20250311-qptj" src="https://github.com/user-attachments/assets/98b1f85e-8911-4908-856e-79e55a4b3156" />
<img width="348" alt="SCR-20250311-quup" src="https://github.com/user-attachments/assets/e5eefac3-a791-4c71-9f49-9d6b86285fff" />


## Caractéristiques

✅ **Design épuré et professionnel** - Interface minimaliste respectant les guidelines d'Apple  
✅ **Mode clair et sombre** - Adaptation automatique au thème de l'appareil  
✅ **Hautement personnalisable** - Couleurs, polices et rayons facilement modifiables  
✅ **Compatibilité iOS 15+** - Fonctionne sur tous les appareils récents

## Éléments inclus

- Écran de connexion principal avec champs email et mot de passe
- Option "Mot de passe oublié"
- Connexion via réseaux sociaux (Google, Facebook, Apple)
- Lien vers l'écran d'inscription
- Options de personnalisation

## Extrait de code

Voici un aperçu du style de code utilisé (version limitée) :

```swift
Circle()
                       .fill()
                       .frame(width: 50, height: 50)
                       .overlay(
                           Circle()
                               .stroke(Color.gray.opacity(0.2), lineWidth: 1)
                       )
                       .overlay(
                           Text(text)
                               .font(.headline)
