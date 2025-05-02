# UIBlendRTImage

**Namespace:** `Torappu.UI`


## Fields

- `BlendWeight _weight`

- `UIBlendRTHost m_host`

- `Boolean m_isRTEnabled`

- `Material m_matForRT`


## Methods

- `Void _UpdateMaterial()`

- `Boolean _IsMeshDisabled()`

- `Void HostOnly_Bind(UIBlendRTHost)`

- `Void HostOnly_Unbind(UIBlendRTHost)`

- `Void HostOnly_SetRTEnabled(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIBlendRTImage : Image
{
	private BlendWeight _weight; // 0x188
	private UIBlendRTHost m_host; // 0x190
	private Boolean m_isRTEnabled; // 0x198
	private Material m_matForRT; // 0x1a0

	public override Boolean packIntoRuntimeAtlas { get; }
	public override Material material { get; set; }

	// RVA: 0x210f5f4 VA: 0x75947275f4
	public override Boolean get_packIntoRuntimeAtlas() { }
	// RVA: 0x210f5fc VA: 0x75947275fc
	public override Material get_material() { }
	// RVA: 0x210f614 VA: 0x7594727614
	public override Void set_material(Material value) { }
	// RVA: 0x210f618 VA: 0x7594727618
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x210f6e8 VA: 0x75947276e8
	private Void _UpdateMaterial() { }
	// RVA: 0x210f664 VA: 0x7594727664
	private Boolean _IsMeshDisabled() { }
	// RVA: 0x210ec70 VA: 0x7594726c70
	public Void HostOnly_Bind(UIBlendRTHost host) { }
	// RVA: 0x210e850 VA: 0x7594726850
	public Void HostOnly_Unbind(UIBlendRTHost host) { }
	// RVA: 0x210eca4 VA: 0x7594726ca4
	public Void HostOnly_SetRTEnabled(Boolean isEnabled) { }
	// RVA: 0x210f780 VA: 0x7594727780
	public Void .ctor() { }
}
```