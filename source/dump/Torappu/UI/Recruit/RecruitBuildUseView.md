# RecruitBuildUseView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _useText`

- `UIItemCard _itemPrefab`

- `Single _itemScale`

- `RectTransform _costItemHolder`

- `RectTransform _costItemHolder_2`

- `UIBlurFloatPanel _float`

- `Int32 m_slotId`

- `UIItemCard m_costItem`

- `UIItemCard m_costItem_2`

- `UIItemViewModel m_costModel`

- `UIItemViewModel m_costModel_2`

- `Boolean m_isInited`

- `UIIntEvent _onClickFast`


## Methods

- `Void OnClick()`

- `Void Dismiss()`

- `Void OnEnter(Int32)`

- `Void _InitIfNot()`

- `Void <_InitIfNot>b__18_0(Int32)`

- `Void <_InitIfNot>b__18_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildUseView : PageSingleComponent
{
	private Text _useText; // 0x20
	private UIItemCard _itemPrefab; // 0x28
	private Single _itemScale; // 0x30
	private RectTransform _costItemHolder; // 0x38
	private RectTransform _costItemHolder_2; // 0x40
	private UIBlurFloatPanel _float; // 0x48
	private Int32 m_slotId; // 0x50
	private UIItemCard m_costItem; // 0x58
	private UIItemCard m_costItem_2; // 0x60
	private UIItemViewModel m_costModel; // 0x68
	private UIItemViewModel m_costModel_2; // 0x70
	private Boolean m_isInited; // 0x78
	private UIIntEvent _onClickFast; // 0x80
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_OnEnterStatic; // 0x8
	private static DelegateBridge __Hotfix0_Dismiss; // 0x10
	private static DelegateBridge __Hotfix0_OnDismissStatic; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2707500 VA: 0x7594d1f500
	public Void OnClick() { }
	// RVA: 0x2707594 VA: 0x7594d1f594
	public static Void OnEnterStatic(Int32 slotId) { }
	// RVA: 0x270781c VA: 0x7594d1f81c
	public Void Dismiss() { }
	// RVA: 0x27078b0 VA: 0x7594d1f8b0
	public static Void OnDismissStatic() { }
	// RVA: 0x2707670 VA: 0x7594d1f670
	public Void OnEnter(Int32 slotId) { }
	// RVA: 0x2707980 VA: 0x7594d1f980
	private Void _InitIfNot() { }
	// RVA: 0x2707ccc VA: 0x7594d1fccc
	public Void .ctor() { }
	// RVA: 0x2707da4 VA: 0x7594d1fda4
	private Void <_InitIfNot>b__18_0(Int32 _) { }
	// RVA: 0x2707ddc VA: 0x7594d1fddc
	private Void <_InitIfNot>b__18_1(Int32 _) { }
}
```