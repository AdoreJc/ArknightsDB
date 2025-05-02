# CrisisV2EntrySeasonResHolder

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Sprite _homeEntry`

- `Sprite _homeEntryMultiMode`

- `Sprite _zoneHomeDaily`


## Methods

- `Sprite GetHomeEntry()`

- `Sprite GetHomeEntryMultiMode()`

- `Sprite GetZoneHomeDailySprite()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntrySeasonResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _homeEntry; // 0x18
	private Sprite _homeEntryMultiMode; // 0x20
	private Sprite _zoneHomeDaily; // 0x28
	private static DelegateBridge __Hotfix0_GetHomeEntry; // 0x0
	private static DelegateBridge __Hotfix0_GetHomeEntryMultiMode; // 0x8
	private static DelegateBridge __Hotfix0_GetZoneHomeDailySprite; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2bc5f14 VA: 0x75951ddf14
	public Sprite GetHomeEntry() { }
	// RVA: 0x2bc5f7c VA: 0x75951ddf7c
	public Sprite GetHomeEntryMultiMode() { }
	// RVA: 0x2bc5fe4 VA: 0x75951ddfe4
	public Sprite GetZoneHomeDailySprite() { }
	// RVA: 0x2bc604c VA: 0x75951de04c
	public Void .ctor() { }
}
```