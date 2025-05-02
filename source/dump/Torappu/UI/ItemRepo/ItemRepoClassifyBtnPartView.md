# ItemRepoClassifyBtnPartView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Transform _onTimeContainer`

- `Single _itemScaler`

- `UIItemTimeCountDown m_countDown`

- `Boolean m_initFlag`


## Methods

- `Void _InitIfNot()`

- `Void _OnTimeExceed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoClassifyBtnPartView : DataBinder`1, IHotfixable
{
	private List`1 _btnView; // 0x20
	private Transform _onTimeContainer; // 0x28
	private Single _itemScaler; // 0x30
	private UIItemTimeCountDown m_countDown; // 0x38
	private Boolean m_initFlag; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnTimeExceed; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d2f138 VA: 0x7595347138
	public Void _InitIfNot() { }
	// RVA: 0x2d2f26c VA: 0x759534726c
	public override Void OnValueChanged(ItemCardGroupViewProperty property) { }
	// RVA: 0x2d2f594 VA: 0x7595347594
	private Void _OnTimeExceed() { }
	// RVA: 0x2d2f634 VA: 0x7595347634
	public Void .ctor() { }
}
```