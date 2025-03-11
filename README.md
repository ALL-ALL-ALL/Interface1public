# Interface de Connexion iOS Minimaliste

Une interface de connexion élégante et minimaliste pour applications iOS, développée avec SwiftUI. Cette interface propose un design épuré et moderne, parfaitement adapté aux applications professionnelles.

![Interface de connexion - Mode clair](login_light_mode.png)
![Interface de connexion - Mode sombre](login_dark_mode.png)

## Caractéristiques

✅ **Design épuré et professionnel** - Interface minimaliste respectant les guidelines d'Apple  
✅ **Mode clair et sombre** - Adaptation automatique au thème de l'appareil  
✅ **Animations fluides** - Transitions élégantes entre les états  
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
struct SocialLoginButton: View {
    var icon: String
    var action: () -> Void
    
    var body: some View {
        Button(action: action) {
            Circle()
                .fill(Color.white)
                .frame(width: 50, height: 50)
                .shadow(color: Color.black.opacity(0.1), radius: 4)
                .overlay(
                    Text(icon)
                        .font(.system(size: 18, weight: .semibold))
                )
        }
    }
}
