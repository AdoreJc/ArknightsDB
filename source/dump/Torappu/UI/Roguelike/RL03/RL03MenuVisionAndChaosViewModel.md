# RL03MenuVisionAndChaosViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String topicId`

- `String curZoneId`

- `String curZoneName`

- `String curZoneIconId`

- `VCWindowViewModel windowViewModel`


## Properties

- `Boolean havePredict`

- `Int32 curChaosLevel`

- `Int32 maxChaosLevel`

- `Int32 sightNum`

- `Int32 maxSightNum`


## Methods

- `Boolean get_havePredict()`

- `Int32 get_curChaosLevel()`

- `Int32 get_maxChaosLevel()`

- `Int32 get_sightNum()`

- `Int32 get_maxSightNum()`

- `Void <>xLuaBaseProxy_LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03MenuVisionAndChaosViewModel : RoguelikeMenuCompViewModel
{
	public String topicId; // 0x18
	public String curZoneId; // 0x20
	public String curZoneName; // 0x28
	public String curZoneIconId; // 0x30
	public VCWindowViewModel windowViewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_havePredict; // 0x0
	private static DelegateBridge __Hotfix0_get_curChaosLevel; // 0x8
	private static DelegateBridge __Hotfix0_get_maxChaosLevel; // 0x10
	private static DelegateBridge __Hotfix0_get_sightNum; // 0x18
	private static DelegateBridge __Hotfix0_get_maxSightNum; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean havePredict { get; }
	public Int32 curChaosLevel { get; }
	public Int32 maxChaosLevel { get; }
	public Int32 sightNum { get; }
	public Int32 maxSightNum { get; }

	// RVA: 0x2b9f174 VA: 0x75951b7174
	public Boolean get_havePredict() { }
	// RVA: 0x2b9f364 VA: 0x75951b7364
	public Int32 get_curChaosLevel() { }
	// RVA: 0x2b9f3dc VA: 0x75951b73dc
	public Int32 get_maxChaosLevel() { }
	// RVA: 0x2b9f234 VA: 0x75951b7234
	public Int32 get_sightNum() { }
	// RVA: 0x2b9f2ac VA: 0x75951b72ac
	public Int32 get_maxSightNum() { }
	// RVA: 0x2ba1778 VA: 0x75951b9778
	public override Void LoadData(String topicId) { }
	// RVA: 0x2ba2000 VA: 0x75951ba000
	public Void .ctor() { }
	// RVA: 0x2ba2134 VA: 0x75951ba134
	private Void <>xLuaBaseProxy_LoadData(String P0) { }
}
```