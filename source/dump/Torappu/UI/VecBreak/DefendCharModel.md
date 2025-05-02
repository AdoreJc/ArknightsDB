# DefendCharModel

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `CharQuery charQuery`

- `EvolvePhase evolvePhase`

- `Int32 instId`

- `String skinId`


## Methods

- `Void LoadFromPlayerDefend(DefendCharInfo, Dictionary`2)`

- `Void LoadFromSquad(SquadItemStruct, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class DefendCharModel : IHotfixable
{
	public CharQuery charQuery; // 0x10
	public EvolvePhase evolvePhase; // 0x28
	public Int32 instId; // 0x2c
	public String skinId; // 0x30
	private static DelegateBridge __Hotfix0_LoadFromPlayerDefend; // 0x0
	private static DelegateBridge __Hotfix0_LoadFromSquad; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22cc550 VA: 0x75948e4550
	public Void LoadFromPlayerDefend(DefendCharInfo info, Dictionary`2 playerChars) { }
	// RVA: 0x22c9d50 VA: 0x75948e1d50
	public Void LoadFromSquad(SquadItemStruct squadItem, Dictionary`2 playerChars) { }
	// RVA: 0x22c9ce0 VA: 0x75948e1ce0
	public Void .ctor() { }
}
```