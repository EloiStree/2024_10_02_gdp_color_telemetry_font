

# Color Telemetry Font

This project provides a **font** that allows exporting game telemetry as colored text. The telemetry data—such as a square array—can be encoded into bytes by the player base.

I plan to implement this in Godot once I understand AssetLib submissions better and get more familiar with Godot. Essentially, I want to recreate what I’ve already coded, but within Godot.

[![Example Image](https://github.com/user-attachments/assets/7418b54b-1069-4baf-85be-aae1ba0b509e)](https://www.youtube.com/watch?v=y0ob7SHFKeg&t=289s)

* Demo: [YouTube Link 1](https://www.youtube.com/watch?v=y0ob7SHFKeg&t=289s)
* Demo: [YouTube Link 2](https://www.youtube.com/watch?v=1WNZ1vsFwXY&t=1051s)

By default, the font encodes **Timestamp, Position, and Rotation**. It can support more than 4 colors, but using more makes LiFi (webcam-based reading) significantly harder.

### Why a font?

Many games allow modding that can draw pixels, but most can display colored text more easily. By using colored text, you can export in-game data—like position, rotation, or Lua-generated colored text—from almost any game.

#### Examples:

* **Unity3D:** [FontColorBytesTelemetryRead](https://github.com/EloiStree/2025_07_29_FontColorBytesTelemetryRead)
* **World of Warcraft:** [TextToColorTelemetry Addon](https://github.com/EloiStree/2025_07_23_WowAddonTextToColorTelemetry)
