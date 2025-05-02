# Act6FunZoneMapAchieveView

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Text _curAchieveCount`

- `Text _totalAchieveCount`

- `SimpleLayoutContent _rewardListContent`

- `SimpleLayoutContent _progressListContent`

- `Boolean m_hasInited`

- `Act6FunZoneMapAchievePluginViewModel m_viewModel`

- `RewardListAdapter m_rewardListAdapter`

- `ProgressListAdapter m_progressListAdapter`


## Methods

- `Void set_onClaimReward(Action`1)`

- `Void Render(Act6FunZoneMapAchievePluginViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapAchieveView : MonoBehaviour, IHotfixable
{
	private Text _curAchieveCount; // 0x18
	private Text _totalAchieveCount; // 0x20
	private SimpleLayoutContent _rewardListContent; // 0x28
	private SimpleLayoutContent _progressListContent; // 0x30
	private Action`1 <onClaimReward>k__BackingField; // 0x38
	private Boolean m_hasInited; // 0x40
	private Act6FunZoneMapAchievePluginViewModel m_viewModel; // 0x48
	private RewardListAdapter m_rewardListAdapter; // 0x50
	private ProgressListAdapter m_progressListAdapter; // 0x58
	private static DelegateBridge __Hotfix0_get_onClaimReward; // 0x0
	private static DelegateBridge __Hotfix0_set_onClaimReward; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClaimReward { get; set; }

	// RVA: 0x31b5f90 VA: 0x75957cdf90
	private Action`1 get_onClaimReward() { }
	// RVA: 0x31b45c0 VA: 0x75957cc5c0
	public Void set_onClaimReward(Action`1 value) { }
	// RVA: 0x31b4644 VA: 0x75957cc644
	public Void Render(Act6FunZoneMapAchievePluginViewModel viewModel) { }
	// RVA: 0x31b5ff8 VA: 0x75957cdff8
	private Void _InitIfNot() { }
	// RVA: 0x31b6244 VA: 0x75957ce244
	public Void .ctor() { }
}
```