# TemplateMissionCommonRewardBasicItemView

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `Transform _itemCont`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`


## Methods

- `Void _InitIfNot()`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonRewardBasicItemView : AbstractTemplateMissionRewardItemView
{
	private Transform _itemCont; // 0x20
	private Boolean m_isInited; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private UIItemViewModel m_itemModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23677d0 VA: 0x759497f7d0
	public override Void Render(AbstractTemplateMissionRewardItemViewModel viewModel) { }
	// RVA: 0x2367968 VA: 0x759497f968
	private Void _InitIfNot() { }
	// RVA: 0x2367bec VA: 0x759497fbec
	private Void _OnItemCardClicked(Int32 unusedIndex) { }
	// RVA: 0x2367ce0 VA: 0x759497fce0
	public Void .ctor() { }
}
```