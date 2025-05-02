# HighlightTile

**Namespace:** `Torappu.Rendering`


## Fields

- `MeshRenderer hlMesh`

- `MaterialPropertyBlock materialPB`

- `Single crtAnmTime`

- `Single crtStrength`


## Methods

- `Void Awake()`

- `IEnumerator IncreaseStrength(Single)`

- `IEnumerator DecreaseStrength(Single, Boolean)`

- `Void SetStrength()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class HighlightTile : HighlightTileBase`1
{
	private static readonly String PROP_STRENGTH; // 0x0
	private MeshRenderer hlMesh; // 0x20
	private MaterialPropertyBlock materialPB; // 0x28
	private Single crtAnmTime; // 0x30
	private Single crtStrength; // 0x34


	// RVA: 0x3f07e00 VA: 0x759651fe00
	public Void Awake() { }
	// RVA: 0x3f07fe0 VA: 0x759651ffe0
	private IEnumerator IncreaseStrength(Single finalAnmTime) { }
	// RVA: 0x3f0808c VA: 0x759652008c
	private IEnumerator DecreaseStrength(Single finalAnmTime, Boolean disableAtEnd) { }
	// RVA: 0x3f0814c VA: 0x759652014c
	public override Void LitOn() { }
	// RVA: 0x3f08224 VA: 0x7596520224
	public override Void LitOff() { }
	// RVA: 0x3f082cc VA: 0x75965202cc
	public override Void SwitchHighlightLevel(Int32 level) { }
	// RVA: 0x3f07f58 VA: 0x759651ff58
	private Void SetStrength() { }
	// RVA: 0x3f082e8 VA: 0x75965202e8
	public Void .ctor() { }
	// RVA: 0x3f08330 VA: 0x7596520330
	private static Void .cctor() { }
}
```