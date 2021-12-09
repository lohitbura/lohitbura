### Hi there 👋


- 🔭 Currently working on Flutter
- 💬 Ask me about ... Mobile Apps, Web Apps
- :heart: Love Cricket , MCU , Tom & Jerry.


// SceneDelegate.swift
import FacebookCore
  ...
func scene(_ scene: UIScene, openURLContexts URLContexts: Set<UIOpenURLContext>) {
    guard let url = URLContexts.first?.url else {
        return
    }

    ApplicationDelegate.shared.application(
        UIApplication.shared,
        open: url,
        sourceApplication: nil,
        annotation: [UIApplication.OpenURLOptionsKey.annotation]
    )
}

