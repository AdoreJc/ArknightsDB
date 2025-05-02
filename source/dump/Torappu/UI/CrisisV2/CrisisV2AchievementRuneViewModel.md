# CrisisV2AchievementRuneViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String iconId`

- `Int32 score`

- `Int32 sortId`

- `String m_runeId`


## Methods

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementRuneViewModel : IHotfixable, IComparable
{
	public String iconId; // 0x10
	public Int32 score; // 0x18
	public Int32 sortId; // 0x1c
	private String m_runeId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8


	// RVA: 0x2be3200 VA: 0x75951fb200
	public Void .ctor(ICrisisV2RuneData data) { }
	// RVA: 0x2be3434 VA: 0x75951fb434
	public Int32 CompareTo(Object obj) { }
}
```