# TextureRegistry

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Texture GetTexture(TextureId)`

- `TextureId AllocAndAcquireDynamic()`

- `Void UpdateDynamic(TextureId, Texture)`

- `TextureId AllocAndAcquire(Texture, Boolean)`

- `TextureId Acquire(Texture)`

- `Void Release(TextureId)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TextureRegistry
{
	private List`1 m_Textures; // 0x10
	private Dictionary`2 m_TextureToId; // 0x18
	private Stack`1 m_FreeIds; // 0x20
	internal const Int32 maxTextures; // 0x0
	private static readonly TextureRegistry <instance>k__BackingField; // 0x0

	public static TextureRegistry instance { get; }

	// RVA: 0x6a0af1c VA: 0x7599022f1c
	public static TextureRegistry get_instance() { }
	// RVA: 0x6a0af74 VA: 0x7599022f74
	public Texture GetTexture(TextureId id) { }
	// RVA: 0x6a051d4 VA: 0x759901d1d4
	public TextureId AllocAndAcquireDynamic() { }
	// RVA: 0x6a0b3ec VA: 0x75990233ec
	public Void UpdateDynamic(TextureId id, Texture texture) { }
	// RVA: 0x6a0b120 VA: 0x7599023120
	private TextureId AllocAndAcquire(Texture texture, Boolean dynamic) { }
	// RVA: 0x6a0b61c VA: 0x759902361c
	public TextureId Acquire(Texture tex) { }
	// RVA: 0x6a05518 VA: 0x759901d518
	public Void Release(TextureId id) { }
	// RVA: 0x6a0b784 VA: 0x7599023784
	public Void .ctor() { }
	// RVA: 0x6a0b8b4 VA: 0x75990238b4
	private static Void .cctor() { }
}
```