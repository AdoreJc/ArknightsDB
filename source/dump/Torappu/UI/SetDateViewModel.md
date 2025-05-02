# SetDateViewModel

**Namespace:** `Torappu.UI`


## Fields

- `SetDateListViewModel monthModel`

- `SetDateListViewModel dayModel`


## Methods

- `Void InitData(Int32, Int32)`

- `Void LoadData()`

- `Void _LoadDays(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SetDateViewModel : IHotfixable
{
	private const Int32 MONTH_IN_YEAR; // 0x0
	private const Int32 SAMPLE_LEAP_YEAR; // 0x0
	public SetDateListViewModel monthModel; // 0x10
	public SetDateListViewModel dayModel; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__LoadDays; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x223c770 VA: 0x7594854770
	public Void InitData(Int32 initMonth, Int32 initDay) { }
	// RVA: 0x223ca9c VA: 0x7594854a9c
	public Void LoadData() { }
	// RVA: 0x223e3b4 VA: 0x75948563b4
	private Void _LoadDays(Int32 curMonth) { }
	// RVA: 0x223e52c VA: 0x759485652c
	public Void .ctor() { }
}
```