# SixStarGroupRewardState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _backRect`

- `SixStarGroupRewardView _rewardView`

- `Boolean m_hasInited`

- `String m_cachedStageId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBackClicked()`

- `Void _EventOnStageRewardClicked(String)`

- `Void _InitIfNot()`

- `Void _OnJumpToStagePreviewReward(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarGroupRewardState : State, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_BACK_BTN_CLICKED; // 0x0
	public const Int32 ON_STAGE_REWARD_CLICKED; // 0x0
	private RectTransform _backRect; // 0x50
	private SixStarGroupRewardView _rewardView; // 0x58
	private Boolean m_hasInited; // 0x60
	private String m_cachedStageId; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBackClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnStageRewardClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToStagePreviewReward; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2f488b0 VA: 0x75955608b0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f48914 VA: 0x7595560914
	protected override Void OnEnter() { }
	// RVA: 0x2f48bf4 VA: 0x7595560bf4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2f48d6c VA: 0x7595560d6c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f48e58 VA: 0x7595560e58
	private Void _EventOnBackClicked() { }
	// RVA: 0x2f48fb4 VA: 0x7595560fb4
	private Void _EventOnStageRewardClicked(String stageId) { }
	// RVA: 0x2f48a28 VA: 0x7595560a28
	private Void _InitIfNot() { }
	// RVA: 0x2f49174 VA: 0x7595561174
	private Void _OnJumpToStagePreviewReward(IStateBean stateBean) { }
	// RVA: 0x2f49298 VA: 0x7595561298
	public Void .ctor() { }
	// RVA: 0x2f49308 VA: 0x7595561308
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f49310 VA: 0x7595561310
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```