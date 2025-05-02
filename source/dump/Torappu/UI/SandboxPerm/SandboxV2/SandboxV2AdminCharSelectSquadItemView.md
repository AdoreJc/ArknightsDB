# SandboxV2AdminCharSelectSquadItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharRepoCharItemView _itemView`

- `Transform _container`

- `GameObject _selectedPart`

- `Text _selectIndex`

- `UIStateFinder m_stateFinder`

- `SandboxV2CharRepoCharItemView m_itemView`

- `Boolean m_isInited`

- `SandboxV2CharViewModel m_viewModel`

- `Int32 m_position`


## Methods

- `Void _InitIfNot()`

- `Void HandleOnClick(Int32)`

- `Void <RenderView>b__10_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminCharSelectSquadItemView : SandboxV2AdminCharSelectAbstractRightItemView
{
	private SandboxV2CharRepoCharItemView _itemView; // 0x18
	private Transform _container; // 0x20
	private GameObject _selectedPart; // 0x28
	private Text _selectIndex; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private SandboxV2CharRepoCharItemView m_itemView; // 0x48
	private Boolean m_isInited; // 0x50
	private SandboxV2CharViewModel m_viewModel; // 0x58
	private Int32 m_position; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0_HandleOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2486d2c VA: 0x7594a9ed2c
	private Void _InitIfNot() { }
	// RVA: 0x2486e14 VA: 0x7594a9ee14
	public override Void RenderView(Int32 position, SandboxV2CharViewModel charViewModel) { }
	// RVA: 0x2486fa4 VA: 0x7594a9efa4
	public Void HandleOnClick(Int32 instId) { }
	// RVA: 0x24870b0 VA: 0x7594a9f0b0
	public Void .ctor() { }
	// RVA: 0x2487120 VA: 0x7594a9f120
	private Void <RenderView>b__10_0(Int32 instId) { }
}
```