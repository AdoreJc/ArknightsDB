# BossRushTeamModel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String teamId`

- `Sprite buffIcon`

- `String buffId`

- `String buffDesc`

- `String buffName`

- `String teamName`

- `Int32 maxCharNum`


## Properties

- `Int32 freeCharNum`


## Methods

- `Int32 get_freeCharNum()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushTeamModel : IHotfixable
{
	public String teamId; // 0x10
	public List`1 teamCharIdList; // 0x18
	public Sprite buffIcon; // 0x20
	public String buffId; // 0x28
	public String buffDesc; // 0x30
	public String buffName; // 0x38
	public String teamName; // 0x40
	public Int32 maxCharNum; // 0x48
	private static DelegateBridge __Hotfix0_get_freeCharNum; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Int32 freeCharNum { get; }

	// RVA: 0x2e79310 VA: 0x7595491310
	public Int32 get_freeCharNum() { }
	// RVA: 0x2e78f94 VA: 0x7595490f94
	public Void .ctor() { }
}
```