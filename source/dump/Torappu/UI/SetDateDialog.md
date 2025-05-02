# SetDateDialog

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _backRt`

- `Text _titleText`

- `SetDateView _view`

- `SetDateProperty m_prop`


## Methods

- `Void DismissSelf()`

- `Void ConfirmDate()`

- `Void _OnMonthItemClicked(Int32)`

- `Void _OnDayItemClicked(Int32)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SetDateDialog : UICompDialog`1
{
	private RectTransform _backRt; // 0x48
	private Text _titleText; // 0x50
	private SetDateView _view; // 0x58
	private SetDateProperty m_prop; // 0x60
	private static DelegateBridge __Hotfix0_DismissSelf; // 0x0
	private static DelegateBridge __Hotfix0_ConfirmDate; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnRender; // 0x18
	private static DelegateBridge __Hotfix0__OnMonthItemClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnDayItemClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x223c168 VA: 0x7594854168
	public Void DismissSelf() { }
	// RVA: 0x223c23c VA: 0x759485423c
	public Void ConfirmDate() { }
	// RVA: 0x223c408 VA: 0x7594854408
	protected override Void OnInit() { }
	// RVA: 0x223c5d8 VA: 0x75948545d8
	protected override Void OnRender(Option options) { }
	// RVA: 0x223c934 VA: 0x7594854934
	private Void _OnMonthItemClicked(Int32 monthPageIdx) { }
	// RVA: 0x223cb6c VA: 0x7594854b6c
	private Void _OnDayItemClicked(Int32 dayPageIdx) { }
	// RVA: 0x223cc58 VA: 0x7594854c58
	public Void .ctor() { }
	// RVA: 0x223cd90 VA: 0x7594854d90
	private Void <>xLuaBaseProxy_OnInit() { }
}
```