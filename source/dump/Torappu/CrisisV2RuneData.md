# CrisisV2RuneData

**Namespace:** `Torappu`


## Fields

- `String runeId`

- `String runeGroupId`

- `String runeIcon`

- `String runeName`

- `Int32 score`

- `Int32 dimension`

- `PackedRuneData packedRune`

- `Int32 sortId`


## Methods

- `String GetRuneId()`

- `Int32 GetRuneScore()`

- `String GetRuneIconId()`

- `Int32 GetRuneSortId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrisisV2RuneData : ICrisisV2RuneData, IHotfixable
{
	public String runeId; // 0x10
	public String runeGroupId; // 0x18
	public String runeIcon; // 0x20
	public String runeName; // 0x28
	public Int32 score; // 0x30
	public Int32 dimension; // 0x34
	public PackedRuneData packedRune; // 0x38
	public Int32 sortId; // 0x40
	private static DelegateBridge __Hotfix0_GetRuneId; // 0x0
	private static DelegateBridge __Hotfix0_GetRuneScore; // 0x8
	private static DelegateBridge __Hotfix0_GetRuneIconId; // 0x10
	private static DelegateBridge __Hotfix0_GetRuneSortId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x349c780 VA: 0x7595ab4780
	public String GetRuneId() { }
	// RVA: 0x349c7e8 VA: 0x7595ab47e8
	public Int32 GetRuneScore() { }
	// RVA: 0x349c850 VA: 0x7595ab4850
	public String GetRuneIconId() { }
	// RVA: 0x349c8b8 VA: 0x7595ab48b8
	public Int32 GetRuneSortId() { }
	// RVA: 0x349c920 VA: 0x7595ab4920
	public Void .ctor() { }
}
```