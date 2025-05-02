# CrisisV2StartServiceConfig

**Namespace:** `Torappu`


## Fields

- `String m_mapId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrisisV2StartServiceConfig : CrisisStartBattleServiceConfig`2
{
	private String m_mapId; // 0x20
	private List`1 m_runeSlotList; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x32ca290 VA: 0x75958e2290
	public Void .ctor(String mapId, List`1 runeSlotList) { }
	// RVA: 0x32ca35c VA: 0x75958e235c
	protected override String get_serviceCode() { }
	// RVA: 0x32ca3d8 VA: 0x75958e23d8
	protected override CrisisV2BattleStartRequest ParseRequest() { }
}
```