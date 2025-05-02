# Act9D0NewsStateBean

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Int32 <unReadNewsCount>k__BackingField`

- `Int32 <unLockedCount>k__BackingField`


## Properties

- `Int32 unReadNewsCount`

- `Int32 unLockedCount`


## Methods

- `Int32 get_unReadNewsCount()`

- `Void set_unReadNewsCount(Int32)`

- `Int32 get_unLockedCount()`

- `Void set_unLockedCount(Int32)`

- `Void LoadData()`

- `Void UpdateNewsStatus(String)`

- `Act9D0NewsViewModel getViewModel(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsStateBean : IStateBean, IHotfixable
{
	public List`1 newsModelList; // 0x10
	private Int32 <unReadNewsCount>k__BackingField; // 0x18
	private Int32 <unLockedCount>k__BackingField; // 0x1c
	private static DelegateBridge __Hotfix0_get_unReadNewsCount; // 0x0
	private static DelegateBridge __Hotfix0_set_unReadNewsCount; // 0x8
	private static DelegateBridge __Hotfix0_get_unLockedCount; // 0x10
	private static DelegateBridge __Hotfix0_set_unLockedCount; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateNewsStatus; // 0x28
	private static DelegateBridge __Hotfix0_getViewModel; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 unReadNewsCount { get; set; }
	public Int32 unLockedCount { get; set; }

	// RVA: 0x31ad7a4 VA: 0x75957c57a4
	public Int32 get_unReadNewsCount() { }
	// RVA: 0x31ad80c VA: 0x75957c580c
	private Void set_unReadNewsCount(Int32 value) { }
	// RVA: 0x31aa9f4 VA: 0x75957c29f4
	public Int32 get_unLockedCount() { }
	// RVA: 0x31ad888 VA: 0x75957c5888
	private Void set_unLockedCount(Int32 value) { }
	// RVA: 0x31ad904 VA: 0x75957c5904
	public Void LoadData() { }
	// RVA: 0x31adf54 VA: 0x75957c5f54
	public Void UpdateNewsStatus(String newsId) { }
	// RVA: 0x31ae130 VA: 0x75957c6130
	public Act9D0NewsViewModel getViewModel(String newsId) { }
	// RVA: 0x31ae244 VA: 0x75957c6244
	public Void .ctor() { }
}
```