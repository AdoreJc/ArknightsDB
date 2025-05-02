# HomeCheckInViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `String title`

- `String description`

- `ProgressCheckInViewModel progressViewModel`

- `Int32 currCheckInIndex`

- `Int32 focusIndex`

- `Boolean isItemGained`

- `Boolean isJustCheckIn`

- `Boolean showProgressGPDetail`

- `String m_groupId`


## Methods

- `Void LoadData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInViewModel : IHotfixable
{
	public String title; // 0x10
	public String description; // 0x18
	public List`1 commonCheckInItemList; // 0x20
	public ProgressCheckInViewModel progressViewModel; // 0x28
	public Int32 currCheckInIndex; // 0x30
	public Int32 focusIndex; // 0x34
	public Boolean isItemGained; // 0x38
	public Boolean isJustCheckIn; // 0x39
	public Boolean showProgressGPDetail; // 0x3a
	private String m_groupId; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x280f28c VA: 0x7594e2728c
	public Void LoadData() { }
	// RVA: 0x280f460 VA: 0x7594e27460
	public Void .ctor() { }
}
```