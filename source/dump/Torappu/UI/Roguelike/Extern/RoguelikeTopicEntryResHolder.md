# RoguelikeTopicEntryResHolder

**Namespace:** `Torappu.UI.Roguelike.Extern`


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
// Namespace : Torappu.UI.Roguelike.Extern
public class RoguelikeTopicEntryResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _homeEntry; // 0x18
	private Sprite _homeEntryMultiMode; // 0x20
	private Sprite _zoneHomeDaily; // 0x28
	private static DelegateBridge __Hotfix0_GetHomeEntry; // 0x0
	private static DelegateBridge __Hotfix0_GetHomeEntryMultiMode; // 0x8
	private static DelegateBridge __Hotfix0_GetZoneHomeDailySprite; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2afa570 VA: 0x7595112570
	public Sprite GetHomeEntry() { }
	// RVA: 0x2afa648 VA: 0x7595112648
	public Sprite GetHomeEntryMultiMode() { }
	// RVA: 0x2afa720 VA: 0x7595112720
	public Sprite GetZoneHomeDailySprite() { }
	// RVA: 0x2afa7f8 VA: 0x75951127f8
	public Void .ctor() { }
}
```