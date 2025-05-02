# BirthdaySettingViewModel

**Namespace:** `Torappu.UI.Birthday`


## Fields

- `Int32 day`

- `Int32 month`

- `Int32 startDay`

- `Int32 startMonth`

- `String name`

- `String desc`

- `String confirmDesc`

- `String leapBirthdayConfirmDesc`

- `Int32 leapBirthdayRewardMonth`

- `Int32 leapBirthdayRewardDay`


## Methods

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Birthday
public class BirthdaySettingViewModel : IHotfixable
{
	public Int32 day; // 0x10
	public Int32 month; // 0x14
	public Int32 startDay; // 0x18
	public Int32 startMonth; // 0x1c
	public String name; // 0x20
	public String desc; // 0x28
	public String confirmDesc; // 0x30
	public String leapBirthdayConfirmDesc; // 0x38
	public Int32 leapBirthdayRewardMonth; // 0x40
	public Int32 leapBirthdayRewardDay; // 0x44
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2e7cfd0 VA: 0x7595494fd0
	public Void InitData() { }
	// RVA: 0x2e7eab8 VA: 0x7595496ab8
	public Void .ctor() { }
}
```