# RoguelikeDungeonPage

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _fadeFloatPanel`

- `RoguelikeEffectManager _effectManager`

- `DataBundle m_savedInst`

- `Boolean m_routeToAnotherPage`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `TEffect AttachRoguelikeEffect(TEffect)`

- `Void EnableMobileTouch(Boolean)`

- `IEnumerator _RouteToProperState()`

- `IEnumerator _JumpToInitProcess()`

- `IEnumerator _HandlePending()`

- `IEnumerator _JumpToSacrificeInChoiceScene()`

- `IEnumerator _JumpToExpeditionInChoiceScene()`

- `IEnumerator _JumpToAlchemy()`

- `IEnumerator _HandleDice()`

- `IEnumerator _RouteToRoguelikeDicePage()`

- `Void _CreateRecruitInput(PlayerRoguelikePendingEvent)`

- `IEnumerator _JumpToRecruitInCommonShop(Boolean)`

- `IEnumerator _JumpToRecruitInBattleReward()`

- `IEnumerator _JumpToRecruitInChoiceScene()`

- `IEnumerator _JumpToReward()`

- `IEnumerator _JumpToCommonShop(Boolean)`

- `IEnumerator _JumpToChoiceScene()`

- `IEnumerator _JumpToFocus()`

- `IEnumerator _JumpToDungeon()`

- `IEnumerator _JumpToEnd()`

- `IEnumerator _EffectOnShow()`

- `IEnumerator _EffectOnHide()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonPage : StateEnginePage, IMobileTouchPage, IHotfixable
{
	private CanvasGroup _fadeFloatPanel; // 0xe8
	private RoguelikeEffectManager _effectManager; // 0xf0
	private DataBundle m_savedInst; // 0xf8
	private Boolean m_routeToAnotherPage; // 0x100
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_AttachRoguelikeEffect; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x18
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x20
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x28
	private static DelegateBridge __Hotfix0_EnableMobileTouch; // 0x30
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x38
	private static DelegateBridge __Hotfix0__JumpToInitProcess; // 0x40
	private static DelegateBridge __Hotfix0__HandlePending; // 0x48
	private static DelegateBridge __Hotfix0__JumpToSacrificeInChoiceScene; // 0x50
	private static DelegateBridge __Hotfix0__JumpToExpeditionInChoiceScene; // 0x58
	private static DelegateBridge __Hotfix0__JumpToAlchemy; // 0x60
	private static DelegateBridge __Hotfix0__HandleDice; // 0x68
	private static DelegateBridge __Hotfix0__RouteToRoguelikeDicePage; // 0x70
	private static DelegateBridge __Hotfix0__CreateRecruitInput; // 0x78
	private static DelegateBridge __Hotfix0__JumpToRecruitInCommonShop; // 0x80
	private static DelegateBridge __Hotfix0__JumpToRecruitInBattleReward; // 0x88
	private static DelegateBridge __Hotfix0__JumpToRecruitInChoiceScene; // 0x90
	private static DelegateBridge __Hotfix0__JumpToReward; // 0x98
	private static DelegateBridge __Hotfix0__JumpToCommonShop; // 0xa0
	private static DelegateBridge __Hotfix0__JumpToChoiceScene; // 0xa8
	private static DelegateBridge __Hotfix0__JumpToFocus; // 0xb0
	private static DelegateBridge __Hotfix0__JumpToDungeon; // 0xb8
	private static DelegateBridge __Hotfix0__JumpToEnd; // 0xc0
	private static DelegateBridge __Hotfix0__EffectOnShow; // 0xc8
	private static DelegateBridge __Hotfix0__EffectOnHide; // 0xd0
	private static DelegateBridge __Hotfix0__AchievePageCanvasGroups; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public String topicId { get; }

	// RVA: 0x2aa7e74 VA: 0x75950bfe74
	public String get_topicId() { }
	// RVA: 0x VA: 0x0
	public TEffect AttachRoguelikeEffect(TEffect effectPrefab) { }
	// RVA: 0x2aae0f8 VA: 0x75950c60f8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2aae194 VA: 0x75950c6194
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2aae268 VA: 0x75950c6268
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x2aae358 VA: 0x75950c6358
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2aae448 VA: 0x75950c6448
	public Void EnableMobileTouch(Boolean enable) { }
	// RVA: 0x2aae550 VA: 0x75950c6550
	private IEnumerator _RouteToProperState() { }
	// RVA: 0x2aae624 VA: 0x75950c6624
	private IEnumerator _JumpToInitProcess() { }
	// RVA: 0x2aae6f8 VA: 0x75950c66f8
	private IEnumerator _HandlePending() { }
	// RVA: 0x2aae7cc VA: 0x75950c67cc
	private IEnumerator _JumpToSacrificeInChoiceScene() { }
	// RVA: 0x2aae8a0 VA: 0x75950c68a0
	private IEnumerator _JumpToExpeditionInChoiceScene() { }
	// RVA: 0x2aae974 VA: 0x75950c6974
	private IEnumerator _JumpToAlchemy() { }
	// RVA: 0x2aaea48 VA: 0x75950c6a48
	private IEnumerator _HandleDice() { }
	// RVA: 0x2aaeb1c VA: 0x75950c6b1c
	private IEnumerator _RouteToRoguelikeDicePage() { }
	// RVA: 0x2aaebf0 VA: 0x75950c6bf0
	private Void _CreateRecruitInput(PlayerRoguelikePendingEvent firstPendingEvent) { }
	// RVA: 0x2aaedc8 VA: 0x75950c6dc8
	private IEnumerator _JumpToRecruitInCommonShop(Boolean canBattle) { }
	// RVA: 0x2aaeeb8 VA: 0x75950c6eb8
	private IEnumerator _JumpToRecruitInBattleReward() { }
	// RVA: 0x2aaef8c VA: 0x75950c6f8c
	private IEnumerator _JumpToRecruitInChoiceScene() { }
	// RVA: 0x2aaf060 VA: 0x75950c7060
	private IEnumerator _JumpToReward() { }
	// RVA: 0x2aaf134 VA: 0x75950c7134
	private IEnumerator _JumpToCommonShop(Boolean canBattle) { }
	// RVA: 0x2aaf224 VA: 0x75950c7224
	private IEnumerator _JumpToChoiceScene() { }
	// RVA: 0x2aaf2f8 VA: 0x75950c72f8
	private IEnumerator _JumpToFocus() { }
	// RVA: 0x2aaf3cc VA: 0x75950c73cc
	private IEnumerator _JumpToDungeon() { }
	// RVA: 0x2aaf4a0 VA: 0x75950c74a0
	private IEnumerator _JumpToEnd() { }
	// RVA: 0x2aaf574 VA: 0x75950c7574
	private IEnumerator _EffectOnShow() { }
	// RVA: 0x2aaf648 VA: 0x75950c7648
	private IEnumerator _EffectOnHide() { }
	// RVA: 0x2aaf71c VA: 0x75950c771c
	private List`1 _AchievePageCanvasGroups() { }
	// RVA: 0x2aaf8f4 VA: 0x75950c78f4
	public Void .ctor() { }
	// RVA: 0x2aaf964 VA: 0x75950c7964
	private IEnumerator <>n__0() { }
	// RVA: 0x2aaf96c VA: 0x75950c796c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2aaf974 VA: 0x75950c7974
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2aaf97c VA: 0x75950c797c
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x2aaf988 VA: 0x75950c7988
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```