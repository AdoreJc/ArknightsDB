# RecruitUpCharSlotSelectViewModel

**Namespace:** `Torappu.UI.Recruit`


## Methods

- `Void InitData()`

- `Boolean IsCharSelectCompleted()`

- `Int32 GetCardDetailDataCount()`

- `RecruitCharSlotCardDetail GetCharCardDetailWithIndex(Int32)`

- `Void SetCardSelectChar(Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitUpCharSlotSelectViewModel : IHotfixable
{
	private const Int32 COUNT_RARITY_SIX; // 0x0
	private const Int32 COUNT_RARITY_FIVE; // 0x0
	private const Int32 INDEX_WITHIN_SHOP; // 0x0
	private List`1 m_charSlotCardDetails; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_IsCharSelectCompleted; // 0x8
	private static DelegateBridge __Hotfix0_GetCardDetailDataCount; // 0x10
	private static DelegateBridge __Hotfix0_GetCharCardDetailWithIndex; // 0x18
	private static DelegateBridge __Hotfix0_GeneRarityCharsDict; // 0x20
	private static DelegateBridge __Hotfix0_SetCardSelectChar; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x26ff0e0 VA: 0x7594d170e0
	public Void InitData() { }
	// RVA: 0x27003f4 VA: 0x7594d183f4
	public Boolean IsCharSelectCompleted() { }
	// RVA: 0x2700bb0 VA: 0x7594d18bb0
	public Int32 GetCardDetailDataCount() { }
	// RVA: 0x26ff504 VA: 0x7594d17504
	public RecruitCharSlotCardDetail GetCharCardDetailWithIndex(Int32 index) { }
	// RVA: 0x2700518 VA: 0x7594d18518
	public Dictionary`2 GeneRarityCharsDict() { }
	// RVA: 0x26ff958 VA: 0x7594d17958
	public Void SetCardSelectChar(Int32 index, String charId) { }
	// RVA: 0x26ff01c VA: 0x7594d1701c
	public Void .ctor() { }
}
```