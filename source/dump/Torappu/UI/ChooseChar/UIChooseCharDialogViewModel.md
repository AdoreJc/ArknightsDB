# UIChooseCharDialogViewModel

**Namespace:** `Torappu.UI.ChooseChar`


## Properties

- `Boolean hasOwnedChars`

- `Boolean hasNotOwnedChars`


## Methods

- `Void set_ownedCharList(List`1)`

- `Void set_notOwnedCharList(List`1)`

- `Boolean get_hasOwnedChars()`

- `Boolean get_hasNotOwnedChars()`

- `Void LoadData(List`1)`

- `Void _SortCharList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIChooseCharDialogViewModel : IHotfixable
{
	private List`1 <ownedCharList>k__BackingField; // 0x10
	private List`1 <notOwnedCharList>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_ownedCharList; // 0x0
	private static DelegateBridge __Hotfix0_set_ownedCharList; // 0x8
	private static DelegateBridge __Hotfix0_get_notOwnedCharList; // 0x10
	private static DelegateBridge __Hotfix0_set_notOwnedCharList; // 0x18
	private static DelegateBridge __Hotfix0_get_hasOwnedChars; // 0x20
	private static DelegateBridge __Hotfix0_get_hasNotOwnedChars; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0__SortCharList; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 ownedCharList { get; set; }
	public List`1 notOwnedCharList { get; set; }
	public Boolean hasOwnedChars { get; }
	public Boolean hasNotOwnedChars { get; }

	// RVA: 0x2c40174 VA: 0x7595258174
	public List`1 get_ownedCharList() { }
	// RVA: 0x2c40b30 VA: 0x7595258b30
	private Void set_ownedCharList(List`1 value) { }
	// RVA: 0x2c4010c VA: 0x759525810c
	public List`1 get_notOwnedCharList() { }
	// RVA: 0x2c40bb4 VA: 0x7595258bb4
	private Void set_notOwnedCharList(List`1 value) { }
	// RVA: 0x2c40c38 VA: 0x7595258c38
	public Boolean get_hasOwnedChars() { }
	// RVA: 0x2c40cc8 VA: 0x7595258cc8
	public Boolean get_hasNotOwnedChars() { }
	// RVA: 0x2c3f944 VA: 0x7595257944
	public Void LoadData(List`1 charIdList) { }
	// RVA: 0x2c40dc8 VA: 0x7595258dc8
	private Void _SortCharList(List`1 viewModelList) { }
	// RVA: 0x2c40970 VA: 0x7595258970
	public Void .ctor() { }
}
```