# UICooperateBattleEmoticonController

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UICooperateBattleEmoticonPanelBtn _emoticonTriggerBtn`

- `Single _predelay`

- `Single _sendingEmojiCD`

- `Single _emojiBtnShowCD`

- `Vector2 _selfPopEmojiOffset`

- `Vector2 _matePopEmojiOffset`

- `Vector2 _matePopEmojiOffsetFootball`

- `Boolean m_isInited`

- `Boolean m_isActive`

- `CooperateUIPlugin m_plugin`

- `PanelInputParam m_cachedPanelInput`

- `IEmoticonCustomConfig m_customConfig`

- `PeriodicTimer m_emojiCDTimer`

- `PeriodicTimer m_emojiBtnShowTimer`

- `PopEmojiItemInputParam m_selfPopEmojiParam`

- `PopEmojiItemInputParam m_matePopEmojiParam`


## Methods

- `Void InitIfNot(Boolean, Boolean)`

- `Void UpdateEmojiCtrl(FP)`

- `Void ShowInBattleEmoticonPanel()`

- `Void _ShowInBattlePopEmojiItem(PopEmojiItemInputParam, String, String)`

- `Void _SendInBattleEmojiRequest(String, String)`

- `Void _OnReceiveEmojiMsg(Object)`

- `Void _ShowEmojiPanelBtn()`

- `Void _HideEmojiPanelBtn(Single)`

- `Void <>xLuaBaseProxy__OnClosePanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleEmoticonController : EmoticonPagerPanelBaseController
{
	private UICooperateBattleEmoticonPanelBtn _emoticonTriggerBtn; // 0x68
	private Single _predelay; // 0x70
	private Single _sendingEmojiCD; // 0x74
	private Single _emojiBtnShowCD; // 0x78
	private Vector2 _selfPopEmojiOffset; // 0x7c
	private Vector2 _matePopEmojiOffset; // 0x84
	private Vector2 _matePopEmojiOffsetFootball; // 0x8c
	private Boolean m_isInited; // 0x94
	private Boolean m_isActive; // 0x95
	private CooperateUIPlugin m_plugin; // 0x98
	private PanelInputParam m_cachedPanelInput; // 0xa0
	private IEmoticonCustomConfig m_customConfig; // 0xa8
	private PeriodicTimer m_emojiCDTimer; // 0xb0
	private PeriodicTimer m_emojiBtnShowTimer; // 0xb8
	private PopEmojiItemInputParam m_selfPopEmojiParam; // 0xc0
	private PopEmojiItemInputParam m_matePopEmojiParam; // 0xc8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_UpdateEmojiCtrl; // 0x8
	private static DelegateBridge __Hotfix0_ShowInBattleEmoticonPanel; // 0x10
	private static DelegateBridge __Hotfix0__ShowInBattlePopEmojiItem; // 0x18
	private static DelegateBridge __Hotfix0__OnSendEmoji; // 0x20
	private static DelegateBridge __Hotfix0__SendInBattleEmojiRequest; // 0x28
	private static DelegateBridge __Hotfix0__OnReceiveEmojiMsg; // 0x30
	private static DelegateBridge __Hotfix0__OnClosePanel; // 0x38
	private static DelegateBridge __Hotfix0__ShowEmojiPanelBtn; // 0x40
	private static DelegateBridge __Hotfix0__HideEmojiPanelBtn; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x20e0a28 VA: 0x75946f8a28
	public Void InitIfNot(Boolean activeEmoticon, Boolean isFootballMode) { }
	// RVA: 0x20e0dd4 VA: 0x75946f8dd4
	public Void UpdateEmojiCtrl(FP deltaTime) { }
	// RVA: 0x20e1128 VA: 0x75946f9128
	public Void ShowInBattleEmoticonPanel() { }
	// RVA: 0x20e1424 VA: 0x75946f9424
	private Void _ShowInBattlePopEmojiItem(PopEmojiItemInputParam popParam, String emojiId, String themeId) { }
	// RVA: 0x20e14f0 VA: 0x75946f94f0
	protected override Void _OnSendEmoji(String themeId, String emojiItem) { }
	// RVA: 0x20e1770 VA: 0x75946f9770
	private Void _SendInBattleEmojiRequest(String themeId, String emojiItem) { }
	// RVA: 0x20e1a08 VA: 0x75946f9a08
	private Void _OnReceiveEmojiMsg(Object arg) { }
	// RVA: 0x20e1b3c VA: 0x75946f9b3c
	protected override Void _OnClosePanel() { }
	// RVA: 0x20e1098 VA: 0x75946f9098
	private Void _ShowEmojiPanelBtn() { }
	// RVA: 0x20e133c VA: 0x75946f933c
	private Void _HideEmojiPanelBtn(Single cd) { }
	// RVA: 0x20e1cfc VA: 0x75946f9cfc
	public Void .ctor() { }
	// RVA: 0x20e1e4c VA: 0x75946f9e4c
	private Void <>xLuaBaseProxy__OnClosePanel() { }
}
```