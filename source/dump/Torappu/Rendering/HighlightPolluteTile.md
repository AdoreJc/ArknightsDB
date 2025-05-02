# HighlightPolluteTile

**Namespace:** `Torappu.Rendering`


## Fields

- `MeshRenderer hlMesh`

- `MaterialPropertyBlock materialPB`

- `Single m_crtAnimRatio`

- `Single m_crtStrength`


## Methods

- `Void Awake()`

- `Void _SetStrength()`

- `Void _DoIncreaseStrength(Single)`

- `IEnumerator _IncreaseStrength(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class HighlightPolluteTile : HighlightTileBase`1
{
	private static readonly String PROP_STRENGTH; // 0x0
	private MeshRenderer hlMesh; // 0x20
	private MaterialPropertyBlock materialPB; // 0x28
	private Single m_crtAnimRatio; // 0x30
	private Single m_crtStrength; // 0x34


	// RVA: 0x3f0774c VA: 0x759651f74c
	public Void Awake() { }
	// RVA: 0x3f07868 VA: 0x759651f868
	public override Void SetHighlightStrength(Single strength) { }
	// RVA: 0x3f07a3c VA: 0x759651fa3c
	private Void _SetStrength() { }
	// RVA: 0x3f07988 VA: 0x759651f988
	private Void _DoIncreaseStrength(Single endStrength) { }
	// RVA: 0x3f07ac4 VA: 0x759651fac4
	private IEnumerator _IncreaseStrength(Single endStrength) { }
	// RVA: 0x3f07b70 VA: 0x759651fb70
	public Void .ctor() { }
	// RVA: 0x3f07bb8 VA: 0x759651fbb8
	private static Void .cctor() { }
}
```