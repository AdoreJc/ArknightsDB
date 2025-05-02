# VectorImageManager

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `VectorImageRenderInfoPool m_RenderInfoPool`

- `GradientRemapPool m_GradientRemapPool`

- `GradientSettingsAtlas m_GradientSettingsAtlas`

- `Boolean m_LoggedExhaustedSettingsAtlas`

- `Boolean <disposed>k__BackingField`


## Properties

- `Texture2D atlas`

- `Boolean disposed`


## Methods

- `Texture2D get_atlas()`

- `Boolean get_disposed()`

- `Void set_disposed(Boolean)`

- `Void Dispose()`

- `Void Commit()`

- `GradientRemap AddUser(VectorImage, VisualElement)`

- `VectorImageRenderInfo Register(VectorImage, VisualElement)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class VectorImageManager : IDisposable
{
	public static List`1 instances; // 0x0
	private static ProfilerMarker s_MarkerRegister; // 0x8
	private static ProfilerMarker s_MarkerUnregister; // 0x10
	private readonly AtlasBase m_Atlas; // 0x10
	private Dictionary`2 m_Registered; // 0x18
	private VectorImageRenderInfoPool m_RenderInfoPool; // 0x20
	private GradientRemapPool m_GradientRemapPool; // 0x28
	private GradientSettingsAtlas m_GradientSettingsAtlas; // 0x30
	private Boolean m_LoggedExhaustedSettingsAtlas; // 0x38
	private Boolean <disposed>k__BackingField; // 0x39

	public Texture2D atlas { get; }
	protected Boolean disposed { get; set; }

	// RVA: 0x695974c VA: 0x7598f7174c
	public Texture2D get_atlas() { }
	// RVA: 0x6959760 VA: 0x7598f71760
	public Void .ctor(AtlasBase atlas) { }
	// RVA: 0x6959960 VA: 0x7598f71960
	protected Boolean get_disposed() { }
	// RVA: 0x6959968 VA: 0x7598f71968
	private Void set_disposed(Boolean value) { }
	// RVA: 0x6959974 VA: 0x7598f71974
	public Void Dispose() { }
	// RVA: 0x69599e0 VA: 0x7598f719e0
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6959af8 VA: 0x7598f71af8
	public Void Commit() { }
	// RVA: 0x6959b28 VA: 0x7598f71b28
	public GradientRemap AddUser(VectorImage vi, VisualElement context) { }
	// RVA: 0x6959c2c VA: 0x7598f71c2c
	private VectorImageRenderInfo Register(VectorImage vi, VisualElement context) { }
	// RVA: 0x695a0f0 VA: 0x7598f720f0
	private static Void .cctor() { }
}
```