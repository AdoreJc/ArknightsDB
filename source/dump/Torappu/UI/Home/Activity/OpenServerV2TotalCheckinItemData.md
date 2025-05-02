# OpenServerV2TotalCheckinItemData

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `TotalCheckinData totalCheckinData`

- `OpenServerCheckinItemState state`


## Methods

- `Boolean IsEmpty()`

- `Int32 GetColorId()`

- `OpenServerItemData GetOpenServerItemData()`

- `OpenServerCheckinItemState GetCheckinState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2TotalCheckinItemData : ICheckinItemData, IHotfixable
{
	public TotalCheckinData totalCheckinData; // 0x10
	public OpenServerCheckinItemState state; // 0x18
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_GetColorId; // 0x8
	private static DelegateBridge __Hotfix0_GetOpenServerItemData; // 0x10
	private static DelegateBridge __Hotfix0_GetCheckinState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28594d4 VA: 0x7594e714d4
	public Boolean IsEmpty() { }
	// RVA: 0x2859554 VA: 0x7594e71554
	public Int32 GetColorId() { }
	// RVA: 0x28595cc VA: 0x7594e715cc
	public OpenServerItemData GetOpenServerItemData() { }
	// RVA: 0x2859644 VA: 0x7594e71644
	public OpenServerCheckinItemState GetCheckinState() { }
	// RVA: 0x28596ac VA: 0x7594e716ac
	public Void .ctor() { }
}
```