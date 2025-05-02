# SixStarRuneSelectGroupViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Int32 level`

- `SixStarRuneSelectGroupStatus status`

- `Boolean isComplete`


## Methods

- `Int32 CompareTo(Object)`

- `Void UnselectAllRune()`

- `Void SetCompleteStatus(PlayerSixStarTagFinishState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarRuneSelectGroupViewModel : IComparable, IHotfixable
{
	public Int32 level; // 0x10
	public SixStarRuneSelectGroupStatus status; // 0x14
	public Boolean isComplete; // 0x18
	public List`1 runeItemModel; // 0x20
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge __Hotfix0_UnselectAllRune; // 0x8
	private static DelegateBridge __Hotfix0_SetCompleteStatus; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f51284 VA: 0x7595569284
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2f50e04 VA: 0x7595568e04
	public Void UnselectAllRune() { }
	// RVA: 0x2f50ee4 VA: 0x7595568ee4
	public Void SetCompleteStatus(PlayerSixStarTagFinishState finishLevel) { }
	// RVA: 0x2f50f6c VA: 0x7595568f6c
	public Void .ctor() { }
}
```