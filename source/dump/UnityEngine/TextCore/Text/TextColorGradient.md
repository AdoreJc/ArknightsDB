# TextColorGradient

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `ColorGradientMode colorMode`

- `Color topLeft`

- `Color topRight`

- `Color bottomLeft`

- `Color bottomRight`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class TextColorGradient : ScriptableObject
{
	public ColorGradientMode colorMode; // 0x18
	public Color topLeft; // 0x1c
	public Color topRight; // 0x2c
	public Color bottomLeft; // 0x3c
	public Color bottomRight; // 0x4c
	private const ColorGradientMode k_DefaultColorMode; // 0x0
	private static readonly Color k_DefaultColor; // 0x0


	// RVA: 0x690687c VA: 0x7598f1e87c
	public Void .ctor() { }
	// RVA: 0x6906918 VA: 0x7598f1e918
	public Void .ctor(Color color) { }
	// RVA: 0x6906984 VA: 0x7598f1e984
	public Void .ctor(Color color0, Color color1, Color color2, Color color3) { }
	// RVA: 0x6906a28 VA: 0x7598f1ea28
	private static Void .cctor() { }
}
```