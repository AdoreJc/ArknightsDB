# SetDateView

**Namespace:** `Torappu.UI`


## Fields

- `SetDatePagerView _monthPagerView`

- `SetDatePagerView _dayPagerView`

- `SetDateItemView _itemPrefab`

- `Boolean m_isInited`

- `Int32 m_cachedMonthIdx`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SetDateView : DataBinder`1
{
	private SetDatePagerView _monthPagerView; // 0x20
	private SetDatePagerView _dayPagerView; // 0x28
	private SetDateItemView _itemPrefab; // 0x30
	public Action`1 onMonthItemClicked; // 0x38
	public Action`1 onDayItemClicked; // 0x40
	private Boolean m_isInited; // 0x48
	private Int32 m_cachedMonthIdx; // 0x4c
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x223e168 VA: 0x7594856168
	public override Void OnValueChanged(SetDateProperty property) { }
	// RVA: 0x223e24c VA: 0x759485624c
	private Void _InitIfNot() { }
	// RVA: 0x223e31c VA: 0x759485631c
	public Void .ctor() { }
}
```