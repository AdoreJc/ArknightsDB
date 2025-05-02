# CharacterLvlupItemCollectionViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterLvlupItemCardViewModel goldItem`


## Properties

- `Int32 expItemCount`

- `Int64 requireGoldCount`


## Methods

- `Int32 get_expItemCount()`

- `Int64 get_requireGoldCount()`

- `Void LoadData()`

- `Int32 CalcCurrentAddExp()`

- `Int32 CalcAddExpFromCounts(Int32[])`

- `Void ChangeToSelectableMode()`

- `Void ChangeToCountingMode()`

- `Void ChangeToDisplayMode()`

- `Void UpdateExpsCountAndGold(Int32[], Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupItemCollectionViewModel : IHotfixable
{
	public CharacterLvlupItemCardViewModel[] expItems; // 0x10
	public CharacterLvlupItemCardViewModel goldItem; // 0x18
	private static DelegateBridge __Hotfix0_get_expItemCount; // 0x0
	private static DelegateBridge __Hotfix0_get_requireGoldCount; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_CalcCurrentAddExp; // 0x18
	private static DelegateBridge __Hotfix0_CalcAddExpFromCounts; // 0x20
	private static DelegateBridge __Hotfix0_ChangeToSelectableMode; // 0x28
	private static DelegateBridge __Hotfix0_ChangeToCountingMode; // 0x30
	private static DelegateBridge __Hotfix0_ChangeToDisplayMode; // 0x38
	private static DelegateBridge __Hotfix0_UpdateExpsCountAndGold; // 0x40
	private static DelegateBridge __Hotfix0_GetExpCountArray; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 expItemCount { get; }
	public Int64 requireGoldCount { get; }

	// RVA: 0x2d5d554 VA: 0x7595375554
	public Int32 get_expItemCount() { }
	// RVA: 0x2d5ed74 VA: 0x7595376d74
	public Int64 get_requireGoldCount() { }
	// RVA: 0x2d5edf0 VA: 0x7595376df0
	public Void LoadData() { }
	// RVA: 0x2d5f3cc VA: 0x75953773cc
	public Int32 CalcCurrentAddExp() { }
	// RVA: 0x2d5f540 VA: 0x7595377540
	public Int32 CalcAddExpFromCounts(Int32[] countArray) { }
	// RVA: 0x2d5f68c VA: 0x759537768c
	public Void ChangeToSelectableMode() { }
	// RVA: 0x2d5f768 VA: 0x7595377768
	public Void ChangeToCountingMode() { }
	// RVA: 0x2d5f848 VA: 0x7595377848
	public Void ChangeToDisplayMode() { }
	// RVA: 0x2d5f928 VA: 0x7595377928
	public Void UpdateExpsCountAndGold(Int32[] countArray, Int64 gold) { }
	// RVA: 0x2d5fa6c VA: 0x7595377a6c
	public Int32[] GetExpCountArray() { }
	// RVA: 0x2d5fb8c VA: 0x7595377b8c
	public Void .ctor() { }
}
```