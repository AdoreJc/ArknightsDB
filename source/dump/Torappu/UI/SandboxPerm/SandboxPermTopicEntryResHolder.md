# SandboxPermTopicEntryResHolder

**Namespace:** `Torappu.UI.SandboxPerm`


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
// Namespace : Torappu.UI.SandboxPerm
public class SandboxPermTopicEntryResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _homeEntry; // 0x18
	private Sprite _homeEntryMultiMode; // 0x20
	private Sprite _zoneHomeDaily; // 0x28
	private static DelegateBridge __Hotfix0_GetHomeEntry; // 0x0
	private static DelegateBridge __Hotfix0_GetHomeEntryMultiMode; // 0x8
	private static DelegateBridge __Hotfix0_GetZoneHomeDailySprite; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x247ecd0 VA: 0x7594a96cd0
	public Sprite GetHomeEntry() { }
	// RVA: 0x247ed38 VA: 0x7594a96d38
	public Sprite GetHomeEntryMultiMode() { }
	// RVA: 0x247eda0 VA: 0x7594a96da0
	public Sprite GetZoneHomeDailySprite() { }
	// RVA: 0x247ee08 VA: 0x7594a96e08
	public Void .ctor() { }
}
```