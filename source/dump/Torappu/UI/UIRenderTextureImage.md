# UIRenderTextureImage

**Namespace:** `Torappu.UI`


## Fields

- `Sprite m_cacheRT`


## Properties

- `Sprite overrideSprite`

- `Color tintColor`

- `Sprite sprite`


## Methods

- `Sprite get_overrideSprite()`

- `Void set_overrideSprite(Sprite)`

- `Color get_tintColor()`

- `Void set_tintColor(Color)`

- `Sprite get_sprite()`

- `Void set_sprite(Sprite)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIRenderTextureImage : Image
{
	private Sprite m_cacheRT; // 0x188

	public Sprite overrideSprite { get; set; }
	public Color tintColor { get; set; }
	public Sprite sprite { get; set; }

	// RVA: 0x21e5e78 VA: 0x75947fde78
	public Sprite get_overrideSprite() { }
	// RVA: 0x21e5e80 VA: 0x75947fde80
	public Void set_overrideSprite(Sprite value) { }
	// RVA: 0x21e5e84 VA: 0x75947fde84
	public Color get_tintColor() { }
	// RVA: 0x21e5ea4 VA: 0x75947fdea4
	public Void set_tintColor(Color value) { }
	// RVA: 0x21e5ef4 VA: 0x75947fdef4
	public Sprite get_sprite() { }
	// RVA: 0x21d5a8c VA: 0x75947eda8c
	public Void set_sprite(Sprite value) { }
	// RVA: 0x21e5efc VA: 0x75947fdefc
	protected override Void OnDestroy() { }
	// RVA: 0x21e5f78 VA: 0x75947fdf78
	public Void .ctor() { }
}
```