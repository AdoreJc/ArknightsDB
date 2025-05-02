# SandboxV2MapConfig

**Namespace:** `Torappu`


## Fields

- `Boolean isRift`

- `Boolean isGuide`

- `Vector2 cameraBoundMin`

- `Vector2 cameraBoundMax`

- `Single cameraMaxNormalizedZoom`

- `String backgroundId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2MapConfig
{
	public static SandboxV2MapConfig DEFAULT; // 0x0
	public static SandboxV2MapConfig RIFT_DEFAULT; // 0x8
	public Boolean isRift; // 0x10
	public Boolean isGuide; // 0x11
	public Vector2 cameraBoundMin; // 0x14
	public Vector2 cameraBoundMax; // 0x1c
	public Single cameraMaxNormalizedZoom; // 0x24
	public String backgroundId; // 0x28


	// RVA: 0x34b22ec VA: 0x7595aca2ec
	public Void .ctor() { }
	// RVA: 0x34b22f4 VA: 0x7595aca2f4
	private static Void .cctor() { }
}
```