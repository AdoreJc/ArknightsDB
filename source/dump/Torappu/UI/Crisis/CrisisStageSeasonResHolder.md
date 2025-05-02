# CrisisStageSeasonResHolder

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `CrisisStageSeasonWidget _entryWidget`

- `CrisisStageSeasonWidget _trainingWidget`

- `Sprite _shopTitle`

- `Sprite _shopEntry`

- `Sprite _seasonIcon`

- `Sprite _medalBtn`


## Methods

- `CrisisStageSeasonWidget GetEntryWidget()`

- `CrisisStageSeasonWidget GetTrainingWidget()`

- `Sprite GetShopTitle()`

- `Sprite GetShopEntry()`

- `Sprite GetSeasonIcon()`

- `Sprite GetMedalIcon()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisStageSeasonResHolder : MonoBehaviour, IHotfixable
{
	private CrisisStageSeasonWidget _entryWidget; // 0x18
	private CrisisStageSeasonWidget _trainingWidget; // 0x20
	private Sprite _shopTitle; // 0x28
	private Sprite _shopEntry; // 0x30
	private Sprite _seasonIcon; // 0x38
	private Sprite _medalBtn; // 0x40
	private static DelegateBridge __Hotfix0_GetEntryWidget; // 0x0
	private static DelegateBridge __Hotfix0_GetTrainingWidget; // 0x8
	private static DelegateBridge __Hotfix0_GetShopTitle; // 0x10
	private static DelegateBridge __Hotfix0_GetShopEntry; // 0x18
	private static DelegateBridge __Hotfix0_GetSeasonIcon; // 0x20
	private static DelegateBridge __Hotfix0_GetMedalIcon; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c376bc VA: 0x759524f6bc
	public CrisisStageSeasonWidget GetEntryWidget() { }
	// RVA: 0x2c37724 VA: 0x759524f724
	public CrisisStageSeasonWidget GetTrainingWidget() { }
	// RVA: 0x2c3778c VA: 0x759524f78c
	public Sprite GetShopTitle() { }
	// RVA: 0x2c377f4 VA: 0x759524f7f4
	public Sprite GetShopEntry() { }
	// RVA: 0x2c3785c VA: 0x759524f85c
	public Sprite GetSeasonIcon() { }
	// RVA: 0x2c378c4 VA: 0x759524f8c4
	public Sprite GetMedalIcon() { }
	// RVA: 0x2c3792c VA: 0x759524f92c
	public Void .ctor() { }
}
```