# MissionTrackPointModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int32 m_finishedMissionNum`

- `Boolean m_isUnlocked`


## Properties

- `Boolean isShow`

- `Int32 finishedMissionNum`


## Methods

- `Boolean get_isShow()`

- `Int32 get_finishedMissionNum()`

- `Boolean RewardAllGet(String)`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class MissionTrackPointModel : ITrackPointModel, IHotfixable
{
	private Int32 m_finishedMissionNum; // 0x10
	private Boolean m_isUnlocked; // 0x14
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_get_finishedMissionNum; // 0x8
	private static DelegateBridge __Hotfix0_MissionEnumeratorCombination; // 0x10
	private static DelegateBridge __Hotfix0_RewardAllGet; // 0x18
	private static DelegateBridge __Hotfix0_UpdateState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isShow { get; }
	public Int32 finishedMissionNum { get; }

	// RVA: 0x281bfa8 VA: 0x7594e33fa8
	public Boolean get_isShow() { }
	// RVA: 0x281c02c VA: 0x7594e3402c
	public Int32 get_finishedMissionNum() { }
	// RVA: 0x281c094 VA: 0x7594e34094
	private IEnumerable`1 MissionEnumeratorCombination(Dictionary`2[] enumerators) { }
	// RVA: 0x281c198 VA: 0x7594e34198
	private Boolean RewardAllGet(String key) { }
	// RVA: 0x281c320 VA: 0x7594e34320
	public Void UpdateState(Object param) { }
	// RVA: 0x281cabc VA: 0x7594e34abc
	public Void .ctor() { }
}
```