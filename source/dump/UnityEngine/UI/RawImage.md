# RawImage

**Namespace:** `UnityEngine.UI`


## Fields

- `Texture m_Texture`

- `Rect m_UVRect`


## Properties

- `Texture texture`

- `Rect uvRect`


## Methods

- `Texture get_texture()`

- `Void set_texture(Texture)`

- `Rect get_uvRect()`

- `Void set_uvRect(Rect)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class RawImage : MaskableGraphic
{
	private Texture m_Texture; // 0xe0
	private Rect m_UVRect; // 0xe8

	public override Texture mainTexture { get; }
	public Texture texture { get; set; }
	public Rect uvRect { get; set; }

	// RVA: 0x6a5c814 VA: 0x7599074814
	protected Void .ctor() { }
	// RVA: 0x6a5c864 VA: 0x7599074864
	public override Texture get_mainTexture() { }
	// RVA: 0x6a5c9bc VA: 0x75990749bc
	public Texture get_texture() { }
	// RVA: 0x6a5c9c4 VA: 0x75990749c4
	public Void set_texture(Texture value) { }
	// RVA: 0x6a5ca80 VA: 0x7599074a80
	public Rect get_uvRect() { }
	// RVA: 0x6a5ca8c VA: 0x7599074a8c
	public Void set_uvRect(Rect value) { }
	// RVA: 0x6a5cb0c VA: 0x7599074b0c
	public override Void SetNativeSize() { }
	// RVA: 0x6a5cdec VA: 0x7599074dec
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x6a5decc VA: 0x7599075ecc
	protected override Void OnDidApplyAnimationProperties() { }
}
```