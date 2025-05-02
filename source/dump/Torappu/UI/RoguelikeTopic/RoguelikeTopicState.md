# RoguelikeTopicState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Transform _entryContainer`

- `Boolean m_isInited`

- `Bridge m_bridge`

- `RoguelikeTopicEntry m_entryView`

- `RoguelikeTopicBasicData m_topicBasicData`


## Methods

- `Coroutine PageOnlyStartShowEffect(Boolean)`

- `Void PageOnlyDisposeEffects()`

- `DisplayParentConfig GetDisplayParentConfig(Boolean)`

- `Void _JumpToMedalGroupState(IStateBean)`

- `String _GetMedalGroupId()`

- `Void _CreateGame(RoguelikeTopicMode, Int32, String)`

- `Void _CloseGame()`

- `Void _SendCloseGameRequest()`

- `Void _ContinueGame()`

- `String _GetCurEnableActivityIdWithMode(RoguelikeTopicMode)`

- `Void _OnSwitchMonthSquadListClicked(Int32)`

- `Void _OnSwitchChallenge(String)`

- `Void _OnOpenWebAnnounce()`

- `Void _OnOpenRogueActivity()`

- `Void _OpenTopicFloatState()`

- `Void _LoadData()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicState : State
{
	private Transform _entryContainer; // 0x50
	private Boolean m_isInited; // 0x58
	private Bridge m_bridge; // 0x60
	private RoguelikeTopicEntry m_entryView; // 0x68
	private RoguelikeTopicBasicData m_topicBasicData; // 0x70
	private static DelegateBridge __Hotfix0_OnResume; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_PageOnlyStartShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_PageOnlyDisposeEffects; // 0x20
	private static DelegateBridge __Hotfix0_GetDisplayParentConfig; // 0x28
	private static DelegateBridge __Hotfix0__JumpToMedalGroupState; // 0x30
	private static DelegateBridge __Hotfix0__GetMedalGroupId; // 0x38
	private static DelegateBridge __Hotfix0__CreateGame; // 0x40
	private static DelegateBridge __Hotfix0__CloseGame; // 0x48
	private static DelegateBridge __Hotfix0__SendCloseGameRequest; // 0x50
	private static DelegateBridge __Hotfix0__ContinueGame; // 0x58
	private static DelegateBridge __Hotfix0__GetCurEnableActivityIdWithMode; // 0x60
	private static DelegateBridge __Hotfix0__OnSwitchMonthSquadListClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnSwitchChallenge; // 0x70
	private static DelegateBridge __Hotfix0__OnOpenWebAnnounce; // 0x78
	private static DelegateBridge __Hotfix0__OnOpenRogueActivity; // 0x80
	private static DelegateBridge __Hotfix0__OpenTopicFloatState; // 0x88
	private static DelegateBridge __Hotfix0__LoadData; // 0x90
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x266f778 VA: 0x7594c87778
	protected override Void OnResume() { }
	// RVA: 0x266fca8 VA: 0x7594c87ca8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x266fe20 VA: 0x7594c87e20
	public override IStateBean GetCacheBean() { }
	// RVA: 0x266f278 VA: 0x7594c87278
	public Coroutine PageOnlyStartShowEffect(Boolean useFastMode) { }
	// RVA: 0x266eecc VA: 0x7594c86ecc
	public Void PageOnlyDisposeEffects() { }
	// RVA: 0x266f314 VA: 0x7594c87314
	public DisplayParentConfig GetDisplayParentConfig(Boolean useFastMode) { }
	// RVA: 0x266fe84 VA: 0x7594c87e84
	private Void _JumpToMedalGroupState(IStateBean rawStateBean) { }
	// RVA: 0x266ff70 VA: 0x7594c87f70
	private String _GetMedalGroupId() { }
	// RVA: 0x2670004 VA: 0x7594c88004
	private Void _CreateGame(RoguelikeTopicMode gameMode, Int32 grade, String predefine) { }
	// RVA: 0x2670518 VA: 0x7594c88518
	private Void _CloseGame() { }
	// RVA: 0x26707c4 VA: 0x7594c887c4
	private Void _SendCloseGameRequest() { }
	// RVA: 0x2670ac4 VA: 0x7594c88ac4
	private Void _ContinueGame() { }
	// RVA: 0x2670328 VA: 0x7594c88328
	private String _GetCurEnableActivityIdWithMode(RoguelikeTopicMode mode) { }
	// RVA: 0x2670bb8 VA: 0x7594c88bb8
	private Void _OnSwitchMonthSquadListClicked(Int32 delta) { }
	// RVA: 0x2670dd0 VA: 0x7594c88dd0
	private Void _OnSwitchChallenge(String challengeId) { }
	// RVA: 0x2670fd4 VA: 0x7594c88fd4
	private Void _OnOpenWebAnnounce() { }
	// RVA: 0x2671054 VA: 0x7594c89054
	private Void _OnOpenRogueActivity() { }
	// RVA: 0x VA: 0x0
	private Void _OpenTopicFloatState() { }
	// RVA: 0x266fa44 VA: 0x7594c87a44
	private Void _LoadData() { }
	// RVA: 0x266f810 VA: 0x7594c87810
	private Void _InitIfNot() { }
	// RVA: 0x2671470 VA: 0x7594c89470
	public Void .ctor() { }
	// RVA: 0x26714e0 VA: 0x7594c894e0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x26714e8 VA: 0x7594c894e8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```