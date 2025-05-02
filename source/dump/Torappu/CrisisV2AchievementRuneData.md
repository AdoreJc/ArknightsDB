# CrisisV2AchievementRuneData

**Namespace:** `Torappu`


## Fields

- `String runeId`

- `String runeIcon`

- `Int32 sortId`

- `Int32 runeScoreSum`


## Methods

- `String GetRuneId()`

- `Int32 GetRuneScore()`

- `String GetRuneIconId()`

- `Int32 GetRuneSortId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrisisV2AchievementRuneData : ICrisisV2RuneData, IHotfixable
{
	public String runeId; // 0x10
	public String runeIcon; // 0x18
	public Int32 sortId; // 0x20
	public Int32 runeScoreSum; // 0x24
	private static DelegateBridge __Hotfix0_GetRuneId; // 0x0
	private static DelegateBridge __Hotfix0_GetRuneScore; // 0x8
	private static DelegateBridge __Hotfix0_GetRuneIconId; // 0x10
	private static DelegateBridge __Hotfix0_GetRuneSortId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x349ce00 VA: 0x7595ab4e00
	public String GetRuneId() { }
	// RVA: 0x349ce68 VA: 0x7595ab4e68
	public Int32 GetRuneScore() { }
	// RVA: 0x349ced0 VA: 0x7595ab4ed0
	public String GetRuneIconId() { }
	// RVA: 0x349cf38 VA: 0x7595ab4f38
	public Int32 GetRuneSortId() { }
	// RVA: 0x349cfa0 VA: 0x7595ab4fa0
	public Void .ctor() { }
}
```