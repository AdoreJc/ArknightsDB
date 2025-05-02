# Act24sideBattleFinishMeldingDropViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String actId`


## Methods

- `Void LoadData(String, Act24sideBattleFinishResponse)`

- `Void _BatchServiceItems(List`1, List`1, Act24sideBattleFinishMeldingDropType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleFinishMeldingDropViewModel : IHotfixable
{
	public List`1 dropItems; // 0x10
	public String actId; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__BatchServiceItems; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x329195c VA: 0x75958a995c
	public Void LoadData(String actId, Act24sideBattleFinishResponse response) { }
	// RVA: 0x3291a64 VA: 0x75958a9a64
	private Void _BatchServiceItems(List`1 serviceItems, List`1 resultList, Act24sideBattleFinishMeldingDropType dropTypeInput) { }
	// RVA: 0x3291d70 VA: 0x75958a9d70
	public Void .ctor() { }
}
```