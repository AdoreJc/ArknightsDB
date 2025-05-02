# Act12D6OuterBuffStateBean

**Namespace:** `Torappu.Activity.Act12D6`


## Methods

- `Void LoadData()`

- `PlayerOuterBuffData GetPlayerOuterBuffData(String)`

- `RoguelikeOuterBuff _GenOuterBuffByLevel(Int32, OuterBuffUnlockInfoData)`

- `PlayerOuterBuffData _GenPlayerOuterBuffData(Int32, OuterBuffUnlockInfoData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6OuterBuffStateBean : IStateBean, IHotfixable
{
	public List`1 outerBuffs; // 0x10
	private const Int32 DEFAULT_BUFF_LEVEL; // 0x0
	private ListDict`2 m_unlockBuffInfos; // 0x18
	private ListDict`2 m_playerBuffInfos; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_GetPlayerOuterBuffData; // 0x8
	private static DelegateBridge __Hotfix0__GenOuterBuffByLevel; // 0x10
	private static DelegateBridge __Hotfix0__GenPlayerOuterBuffData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x347d148 VA: 0x7595a95148
	public Void LoadData() { }
	// RVA: 0x347da6c VA: 0x7595a95a6c
	public PlayerOuterBuffData GetPlayerOuterBuffData(String buffId) { }
	// RVA: 0x347d794 VA: 0x7595a95794
	private RoguelikeOuterBuff _GenOuterBuffByLevel(Int32 level, OuterBuffUnlockInfoData unlockInfos) { }
	// RVA: 0x347d990 VA: 0x7595a95990
	private PlayerOuterBuffData _GenPlayerOuterBuffData(Int32 level, OuterBuffUnlockInfoData unlockInfos) { }
	// RVA: 0x347db84 VA: 0x7595a95b84
	public Void .ctor() { }
}
```