# ProgressCheckInViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Boolean isValid`

- `Int32 currentCheckInDay`

- `String title`

- `String remainTimeDesc`

- `String iconId`


## Methods

- `Void LoadData()`

- `Void _Reset()`

- `Boolean _TryLoadReturnProgressData()`

- `Boolean _TryLoadNewProgressData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class ProgressCheckInViewModel : IHotfixable
{
	private const Int32 DAY_THRES; // 0x0
	public List`1 itemList; // 0x10
	public Boolean isValid; // 0x18
	public Int32 currentCheckInDay; // 0x1c
	public String title; // 0x20
	public String remainTimeDesc; // 0x28
	public String iconId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__Reset; // 0x8
	private static DelegateBridge __Hotfix0__TryLoadReturnProgressData; // 0x10
	private static DelegateBridge __Hotfix0__TryLoadNewProgressData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x280e0b0 VA: 0x7594e260b0
	public Void LoadData() { }
	// RVA: 0x280e13c VA: 0x7594e2613c
	private Void _Reset() { }
	// RVA: 0x280e1e0 VA: 0x7594e261e0
	private Boolean _TryLoadReturnProgressData() { }
	// RVA: 0x280e95c VA: 0x7594e2695c
	private Boolean _TryLoadNewProgressData() { }
	// RVA: 0x280f100 VA: 0x7594e27100
	public Void .ctor() { }
}
```