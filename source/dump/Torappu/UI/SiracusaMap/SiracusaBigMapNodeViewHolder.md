# SiracusaBigMapNodeViewHolder

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapNodeViewBase m_normalNodeView`

- `SiracusaMapNodeViewBase m_selectedNodeView`

- `SiracusaMapNodeViewBase m_taskNodeView`

- `NodeModelStruct m_nodeModelStruct`

- `SiracusaMapNodeViewBase m_curNodeView`

- `AutoPackSpriteHub <taskCharAvatarHub>k__BackingField`


## Properties

- `AutoPackSpriteHub taskCharAvatarHub`


## Methods

- `Void set_onNodeClick(Action`1)`

- `AutoPackSpriteHub get_taskCharAvatarHub()`

- `Void set_taskCharAvatarHub(AutoPackSpriteHub)`

- `SiracusaMapNodeViewBase _LoadNodeView(NodeType, Boolean)`

- `Void _OnBigMapNodeClicked(SiracusaMapMapNodeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapNodeViewHolder : SiracusaMapNodeViewHolder
{
	private SiracusaMapNodeViewBase m_normalNodeView; // 0x58
	private SiracusaMapNodeViewBase m_selectedNodeView; // 0x60
	private SiracusaMapNodeViewBase m_taskNodeView; // 0x68
	private NodeModelStruct m_nodeModelStruct; // 0x70
	private SiracusaMapNodeViewBase m_curNodeView; // 0xc0
	private Action`1 <onNodeClick>k__BackingField; // 0xc8
	private AutoPackSpriteHub <taskCharAvatarHub>k__BackingField; // 0xd0
	private static DelegateBridge __Hotfix0_get_onNodeClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onNodeClick; // 0x8
	private static DelegateBridge __Hotfix0_get_taskCharAvatarHub; // 0x10
	private static DelegateBridge __Hotfix0_set_taskCharAvatarHub; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x28
	private static DelegateBridge __Hotfix0__LoadNodeView; // 0x30
	private static DelegateBridge __Hotfix0__OnBigMapNodeClicked; // 0x38
	private static DelegateBridge __Hotfix0__CheckIfNeedAnim; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onNodeClick { get; set; }
	protected AutoPackSpriteHub taskCharAvatarHub { get; set; }

	// RVA: 0x240aa58 VA: 0x7594a22a58
	private Action`1 get_onNodeClick() { }
	// RVA: 0x240aac0 VA: 0x7594a22ac0
	public Void set_onNodeClick(Action`1 value) { }
	// RVA: 0x240ab44 VA: 0x7594a22b44
	protected AutoPackSpriteHub get_taskCharAvatarHub() { }
	// RVA: 0x240abac VA: 0x7594a22bac
	public Void set_taskCharAvatarHub(AutoPackSpriteHub value) { }
	// RVA: 0x240ac30 VA: 0x7594a22c30
	public override Void Render(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240b2e4 VA: 0x7594a232e4
	public override Void Reset() { }
	// RVA: 0x240ae7c VA: 0x7594a22e7c
	private SiracusaMapNodeViewBase _LoadNodeView(NodeType nodeType, Boolean isSelected) { }
	// RVA: 0x240b47c VA: 0x7594a2347c
	private Void _OnBigMapNodeClicked(SiracusaMapMapNodeViewModel viewModel) { }
	// RVA: 0x240b204 VA: 0x7594a23204
	private static Boolean _CheckIfNeedAnim(NodeModelStruct prevViewModel, NodeModelStruct newViewModel) { }
	// RVA: 0x240b534 VA: 0x7594a23534
	public Void .ctor() { }
}
```