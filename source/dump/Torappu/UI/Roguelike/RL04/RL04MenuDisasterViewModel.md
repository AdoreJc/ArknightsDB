# RL04MenuDisasterViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `String topicId`

- `String currentZoneId`

- `String currentZoneName`

- `String currentZoneIconId`

- `Int32 disperseStep`

- `String m_disasterId`

- `RoguelikeDisasterData m_disasterData`


## Properties

- `Boolean haveDisaster`

- `String disasterId`

- `String disasterName`

- `String disasterIconId`

- `Int32 disasterLevel`

- `String disasterDesc`

- `String disasterFuncDesc`


## Methods

- `Boolean get_haveDisaster()`

- `String get_disasterId()`

- `String get_disasterName()`

- `String get_disasterIconId()`

- `Int32 get_disasterLevel()`

- `String get_disasterDesc()`

- `String get_disasterFuncDesc()`

- `Void _LoadDisasterData(String, CurrentData)`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04MenuDisasterViewModel : RoguelikeMenuCompViewModel
{
	public String topicId; // 0x18
	public String currentZoneId; // 0x20
	public String currentZoneName; // 0x28
	public String currentZoneIconId; // 0x30
	public Int32 disperseStep; // 0x38
	private String m_disasterId; // 0x40
	private RoguelikeDisasterData m_disasterData; // 0x48
	private static DelegateBridge __Hotfix0_get_haveDisaster; // 0x0
	private static DelegateBridge __Hotfix0_get_disasterId; // 0x8
	private static DelegateBridge __Hotfix0_get_disasterName; // 0x10
	private static DelegateBridge __Hotfix0_get_disasterIconId; // 0x18
	private static DelegateBridge __Hotfix0_get_disasterLevel; // 0x20
	private static DelegateBridge __Hotfix0_get_disasterDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_disasterFuncDesc; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0__LoadDisasterData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean haveDisaster { get; }
	public String disasterId { get; }
	public String disasterName { get; }
	public String disasterIconId { get; }
	public Int32 disasterLevel { get; }
	public String disasterDesc { get; }
	public String disasterFuncDesc { get; }

	// RVA: 0x2b2a29c VA: 0x759514229c
	public Boolean get_haveDisaster() { }
	// RVA: 0x2b2aa28 VA: 0x7595142a28
	public String get_disasterId() { }
	// RVA: 0x2b2dc98 VA: 0x7595145c98
	public String get_disasterName() { }
	// RVA: 0x2b2a628 VA: 0x7595142628
	public String get_disasterIconId() { }
	// RVA: 0x2b2a6a0 VA: 0x75951426a0
	public Int32 get_disasterLevel() { }
	// RVA: 0x2b2dd88 VA: 0x7595145d88
	public String get_disasterDesc() { }
	// RVA: 0x2b2dd10 VA: 0x7595145d10
	public String get_disasterFuncDesc() { }
	// RVA: 0x2b2e56c VA: 0x759514656c
	public override Void LoadData(String topicId) { }
	// RVA: 0x2b2e7f0 VA: 0x75951467f0
	private Void _LoadDisasterData(String topicId, CurrentData playerRoguelike) { }
	// RVA: 0x2b2e9cc VA: 0x75951469cc
	public Void .ctor() { }
	// RVA: 0x2b2ea3c VA: 0x7595146a3c
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```