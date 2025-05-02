# RoguelikeEntryState

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `RoguelikeEntryBottomView _bottomView`

- `RoguelikeEntryMainView _mainView`

- `RectTransform _panelBack`

- `RoguelikeEntryStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnItemClicked(String)`

- `Void _OnEntryClicked(String)`

- `Void _OnPinBtnClicked()`

- `Void _OnArchiveBtnClicked()`

- `Void _InitIfNot()`

- `Void _OnBackClicked()`

- `Void _HandleTopicPinnedRequest(String, Action)`

- `Void _ShowPinToast(String, Boolean)`

- `Void _ShowJudgeDialog(String, String, Action)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryState : State, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_ITEM_CLICKED; // 0x0
	public const Int32 ON_ENTRY_CLICKED; // 0x0
	public const Int32 ON_PIN_BTN_CLICKED; // 0x0
	public const Int32 ON_ARCHIVE_BTN_CLICKED; // 0x0
	private RoguelikeEntryBottomView _bottomView; // 0x50
	private RoguelikeEntryMainView _mainView; // 0x58
	private RectTransform _panelBack; // 0x60
	private RoguelikeEntryStateBean m_stateBean; // 0x68
	private Boolean m_hasInited; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnEntryClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnPinBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnArchiveBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OnBackClicked; // 0x48
	private static DelegateBridge __Hotfix0__HandleTopicPinnedRequest; // 0x50
	private static DelegateBridge __Hotfix0__ShowPinToast; // 0x58
	private static DelegateBridge __Hotfix0__ShowJudgeDialog; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x262da6c VA: 0x7594c45a6c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x262dad4 VA: 0x7594c45ad4
	protected override Void OnEnter() { }
	// RVA: 0x262dd94 VA: 0x7594c45d94
	protected override Void OnResume() { }
	// RVA: 0x262defc VA: 0x7594c45efc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x262e048 VA: 0x7594c46048
	private Void _OnItemClicked(String topicId) { }
	// RVA: 0x262e1b0 VA: 0x7594c461b0
	private Void _OnEntryClicked(String topicId) { }
	// RVA: 0x262e3d8 VA: 0x7594c463d8
	private Void _OnPinBtnClicked() { }
	// RVA: 0x262e66c VA: 0x7594c4666c
	private Void _OnArchiveBtnClicked() { }
	// RVA: 0x262dc5c VA: 0x7594c45c5c
	private Void _InitIfNot() { }
	// RVA: 0x262edc8 VA: 0x7594c46dc8
	private Void _OnBackClicked() { }
	// RVA: 0x262e938 VA: 0x7594c46938
	private Void _HandleTopicPinnedRequest(String topicId, Action onComplete) { }
	// RVA: 0x262ef30 VA: 0x7594c46f30
	private Void _ShowPinToast(String topicId, Boolean isPinned) { }
	// RVA: 0x262ebf8 VA: 0x7594c46bf8
	private Void _ShowJudgeDialog(String prevTopic, String nextTopic, Action onPositive) { }
	// RVA: 0x262f014 VA: 0x7594c47014
	public Void .ctor() { }
	// RVA: 0x262f170 VA: 0x7594c47170
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x262f178 VA: 0x7594c47178
	private Void <>xLuaBaseProxy_OnResume() { }
}
```