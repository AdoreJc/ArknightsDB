# SandboxV2CharSelectLogisticsRightItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharRepoAbstractItemView _itemView`

- `Transform _container`

- `GameObject _selectedPart`

- `Text _selectIndex`

- `UIStateFinder m_stateFinder`

- `SandboxV2CharRepoAbstractItemView m_itemView`

- `Boolean m_isInited`

- `SandboxV2CharViewModel m_viewModel`

- `Int32 m_position`


## Methods

- `Void _InitIfNot()`

- `Void _HandleOnClick(Int32)`

- `Void <RenderView>b__10_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectLogisticsRightItemView : SandboxV2AdminCharSelectAbstractRightItemView
{
	private SandboxV2CharRepoAbstractItemView _itemView; // 0x18
	private Transform _container; // 0x20
	private GameObject _selectedPart; // 0x28
	private Text _selectIndex; // 0x30
	private UIStateFinder m_stateFinder; // 0x38
	private SandboxV2CharRepoAbstractItemView m_itemView; // 0x48
	private Boolean m_isInited; // 0x50
	private SandboxV2CharViewModel m_viewModel; // 0x58
	private Int32 m_position; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__HandleOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2484004 VA: 0x7594a9c004
	private Void _InitIfNot() { }
	// RVA: 0x24840ec VA: 0x7594a9c0ec
	public override Void RenderView(Int32 position, SandboxV2CharViewModel charViewModel) { }
	// RVA: 0x248427c VA: 0x7594a9c27c
	private Void _HandleOnClick(Int32 instId) { }
	// RVA: 0x2484388 VA: 0x7594a9c388
	public Void .ctor() { }
	// RVA: 0x24843f8 VA: 0x7594a9c3f8
	private Void <RenderView>b__10_0(Int32 instId) { }
}
```