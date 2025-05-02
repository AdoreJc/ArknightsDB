# EditorSettings

**Namespace:** ` `


## Fields

- `Double m_Framerate`

- `Boolean m_ScenePreview`


## Properties

- `Double frameRate`


## Methods

- `Double get_frameRate()`

- `Void set_frameRate(Double)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : 
public class EditorSettings
{
	internal static readonly Double kMinFrameRate; // 0x0
	internal static readonly Double kMaxFrameRate; // 0x8
	internal static readonly Double kDefaultFrameRate; // 0x10
	private Double m_Framerate; // 0x10
	private Boolean m_ScenePreview; // 0x18

	public Double frameRate { get; set; }

	// RVA: 0x6827178 VA: 0x7598e3f178
	public Double get_frameRate() { }
	// RVA: 0x6823d38 VA: 0x7598e3bd38
	public Void set_frameRate(Double value) { }
	// RVA: 0x6827108 VA: 0x7598e3f108
	public Void .ctor() { }
	// RVA: 0x6827180 VA: 0x7598e3f180
	private static Void .cctor() { }
}
```