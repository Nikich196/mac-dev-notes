# iOS 27: UIScene обязателен

Приложение, собранное с SDK iOS 27 без жизненного цикла UIScene, падает при старте (EXC_BREAKPOINT в _UIApplicationEvaluateRuntimeIssueForNoSceneLifecycleAdoption). SwiftUI-приложения его уже используют; старым шаблонам (например, React Native/Expo) нужно обновление.
