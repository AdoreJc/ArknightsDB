# AlphaSplitImageHolder

**Namespace:** `Torappu.AVG`


## Fields

- `Image m_image`

- `Material m_alphaSplitMaterial`

- `PostDisplayHandler m_postDisplay`

- `ShaderLoadType <loadType>k__BackingField`


## Properties

- `Image image`

- `ShaderLoadType loadType`

- `Material charMaterial`


## Methods

- `Image get_image()`

- `ShaderLoadType get_loadType()`

- `Void set_loadType(ShaderLoadType)`

- `Void SetSprite(SpriteConfig, SpriteConfig, CharSpriteConfig)`

- `Void Clear()`

- `Void Reset()`

- `Void BindPostDisplay(String, AVGCompBridge)`

- `Material get_charMaterial()`

- `Void set_charMaterial(Material)`

- `UIShaderProfile _LoadShaderProfile()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AlphaSplitImageHolder
{
	private Image m_image; // 0x10
	private Material m_alphaSplitMaterial; // 0x18
	private PostDisplayHandler m_postDisplay; // 0x20
	private ShaderLoadType <loadType>k__BackingField; // 0x28

	public Image image { get; }
	private ShaderLoadType loadType { get; set; }
	public Material charMaterial { get; set; }

	// RVA: 0x3e9eb08 VA: 0x75964b6b08
	public Image get_image() { }
	// RVA: 0x3e9eb10 VA: 0x75964b6b10
	private ShaderLoadType get_loadType() { }
	// RVA: 0x3e9eb18 VA: 0x75964b6b18
	public Void set_loadType(ShaderLoadType value) { }
	// RVA: 0x3e9eb20 VA: 0x75964b6b20
	public Void SetSprite(SpriteConfig config, SpriteConfig faceConfig, CharSpriteConfig spriteConfig) { }
	// RVA: 0x3e9cfa0 VA: 0x75964b4fa0
	public Void .ctor(Image image) { }
	// RVA: 0x3e9f100 VA: 0x75964b7100
	public Void Clear() { }
	// RVA: 0x3e9f1f0 VA: 0x75964b71f0
	public Void Reset() { }
	// RVA: 0x3e9f2c4 VA: 0x75964b72c4
	public Void BindPostDisplay(String channel, AVGCompBridge bridge) { }
	// RVA: 0x3e9f37c VA: 0x75964b737c
	public Material get_charMaterial() { }
	// RVA: 0x3e9f384 VA: 0x75964b7384
	public Void set_charMaterial(Material value) { }
	// RVA: 0x3e9ef4c VA: 0x75964b6f4c
	private UIShaderProfile _LoadShaderProfile() { }
}
```