# MedalTypeViewModel

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalCount m_medalCount`

- `MedalTypeData typeData`


## Properties

- `Int32 sortId`

- `String typeId`

- `Int32 totalCount`

- `Int32 getCount`

- `Int32 achievedHiddenCount`


## Methods

- `Int32 get_sortId()`

- `String get_typeId()`

- `Int32 get_totalCount()`

- `Int32 get_getCount()`

- `Int32 get_achievedHiddenCount()`

- `Void AddMedalData(MedalCommonViewModel, Int64)`

- `Void SetMedalCount(MedalCount)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalTypeViewModel : IHotfixable
{
	private MedalCount m_medalCount; // 0x10
	public MedalTypeData typeData; // 0x20
	public List`1 groupViewModelList; // 0x28
	private static DelegateBridge __Hotfix0_get_sortId; // 0x0
	private static DelegateBridge __Hotfix0_get_typeId; // 0x8
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x10
	private static DelegateBridge __Hotfix0_get_getCount; // 0x18
	private static DelegateBridge __Hotfix0_get_achievedHiddenCount; // 0x20
	private static DelegateBridge __Hotfix0_AddMedalData; // 0x28
	private static DelegateBridge __Hotfix0_SetMedalCount; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 sortId { get; }
	public String typeId { get; }
	public Int32 totalCount { get; }
	public Int32 getCount { get; }
	public Int32 achievedHiddenCount { get; }

	// RVA: 0x27aacc8 VA: 0x7594dc2cc8
	public Int32 get_sortId() { }
	// RVA: 0x27a4580 VA: 0x7594dbc580
	public String get_typeId() { }
	// RVA: 0x27a7cec VA: 0x7594dbfcec
	public Int32 get_totalCount() { }
	// RVA: 0x27a7c60 VA: 0x7594dbfc60
	public Int32 get_getCount() { }
	// RVA: 0x27a7bd4 VA: 0x7594dbfbd4
	public Int32 get_achievedHiddenCount() { }
	// RVA: 0x27aad3c VA: 0x7594dc2d3c
	public Void AddMedalData(MedalCommonViewModel viewModel, Int64 curTs) { }
	// RVA: 0x27ab174 VA: 0x7594dc3174
	public Void SetMedalCount(MedalCount medalCount) { }
	// RVA: 0x27ab1fc VA: 0x7594dc31fc
	public Void .ctor() { }
}
```