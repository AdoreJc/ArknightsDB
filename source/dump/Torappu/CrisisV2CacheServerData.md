# CrisisV2CacheServerData

**Namespace:** `Torappu`


## Fields

- `String seasonId`

- `CrisisV2SeasonConstData seasonConst`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CrisisV2CacheServerData : IHotfixable
{
	public String seasonId; // 0x10
	public Dictionary`2 mapStageDataMap; // 0x18
	public Dictionary`2 mapDetailDataMap; // 0x20
	public Dictionary`2 achievementDataMap; // 0x28
	public CrisisV2SeasonConstData seasonConst; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x349d444 VA: 0x7595ab5444
	public Void .ctor() { }
}
```