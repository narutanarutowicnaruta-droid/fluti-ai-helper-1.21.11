# Fluti AI Helper (Fabric 1.21.11)

Personal Fabric 1.21.11 companion mod setup:
- **Key `0`**: Opens `BotControlScreen` to spawn the bot and clear tasks.
- **Chat commands (intercepted locally, not sent to public chat)**:
  - `.добыть дерево` / `.добути дерево` / `.mine wood`
  - `.добыть камень` / `.добути камінь` / `.mine stone`
  - `.добыть железо` / `.добути залізо` / `.mine iron`
  - `.стоп` / `.стій` / `.stop`
- **Blockbench**: Export your entity model to `HelperBotModel.java` and place your texture at `src/main/resources/assets/fluti_ai/textures/entity/helper_bot.png`.
- **GitHub Actions**: `.github/workflows/build.yml` builds the mod JAR using Java 21 (add `gradlew` and `gradle/` wrapper files from a standard Fabric template or run `gradle wrapper` locally).
