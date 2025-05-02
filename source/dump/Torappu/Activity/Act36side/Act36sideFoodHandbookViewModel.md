# Act36sideFoodHandbookViewModel

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Act36sideFoodHandbookTabType currentActiveTab`

- `Int32 unlockedItemNum`

- `Int32 totalItemNum`

- `String selectedTokenId`

- `RewardState rewardState`

- `String activityId`

- `String unfinishToast`

- `Boolean isEnemyTabShowNew`

- `Boolean isTokenTabShowNew`


## Methods

- `Void LoadData(String)`

- `Void RefreshData()`

- `Void SelectTab(Act36sideFoodHandbookTabType)`

- `Void SelectTokenItem(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideFoodHandbookViewModel : IHotfixable
{
	public ListDict`2 enemyDict; // 0x10
	public ListDict`2 tokenDict; // 0x18
	public Act36sideFoodHandbookTabType currentActiveTab; // 0x20
	public Int32 unlockedItemNum; // 0x24
	public Int32 totalItemNum; // 0x28
	public String selectedTokenId; // 0x30
	public RewardState rewardState; // 0x38
	public String activityId; // 0x40
	public String unfinishToast; // 0x48
	public Boolean isEnemyTabShowNew; // 0x50
	public Boolean isTokenTabShowNew; // 0x51
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge __Hotfix0_SelectTab; // 0x10
	private static DelegateBridge __Hotfix0_SelectTokenItem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32453e0 VA: 0x759585d3e0
	public Void LoadData(String actId) { }
	// RVA: 0x3246bc0 VA: 0x759585ebc0
	public Void RefreshData() { }
	// RVA: 0x3246620 VA: 0x759585e620
	public Void SelectTab(Act36sideFoodHandbookTabType selectedTabType) { }
	// RVA: 0x3246758 VA: 0x759585e758
	public Void SelectTokenItem(String selectedTokenId) { }
	// RVA: 0x3246fec VA: 0x759585efec
	public Void .ctor() { }
}
```