# UIImageFastRectMask

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _bestFitRect`

- `Image m_image`


## Properties

- `Image image`


## Methods

- `Image get_image()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIImageFastRectMask : BaseMeshEffect
{
	private RectTransform _bestFitRect; // 0x20
	private Image m_image; // 0x28

	private Image image { get; }

	// RVA: 0x21d6b30 VA: 0x75947eeb30
	private Image get_image() { }
	// RVA: 0x21d6bd8 VA: 0x75947eebd8
	protected override Void Awake() { }
	// RVA: 0x21d6be0 VA: 0x75947eebe0
	public override Void ModifyMesh(VertexHelper vh) { }
	// RVA: 0x21d7db0 VA: 0x75947efdb0
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x21d7de4 VA: 0x75947efde4
	public Void .ctor() { }
}
```