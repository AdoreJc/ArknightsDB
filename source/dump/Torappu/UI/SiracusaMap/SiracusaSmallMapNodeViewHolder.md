# SiracusaSmallMapNodeViewHolder

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapNodeViewBase m_normalNodeView`

- `SiracusaMapNodeViewBase m_selectedNodeView`

- `NodeModelStruct m_nodeModelStruct`

- `SiracusaMapNodeViewBase m_curNodeView`


## Methods

- `SiracusaMapNodeViewBase _LoadNodeView(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaSmallMapNodeViewHolder : SiracusaMapNodeViewHolder
{
	private SiracusaMapNodeViewBase m_normalNodeView; // 0x58
	private SiracusaMapNodeViewBase m_selectedNodeView; // 0x60
	private NodeModelStruct m_nodeModelStruct; // 0x68
	private SiracusaMapNodeViewBase m_curNodeView; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0__LoadNodeView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2414d98 VA: 0x7594a2cd98
	public override Void Render(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x2415384 VA: 0x7594a2d384
	public override Void Reset() { }
	// RVA: 0x24151ec VA: 0x7594a2d1ec
	private SiracusaMapNodeViewBase _LoadNodeView(Boolean isSelected) { }
	// RVA: 0x2415498 VA: 0x7594a2d498
	public Void .ctor() { }
}
```