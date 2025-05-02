# ArchiveChatListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `CanvasGroup _panelFadeSwitch`

- `ArchiveChatDetailItemView _viewDetail`

- `RoguelikeTopicMonthSquadCharPortraitView _charPrefab`

- `Transform _charContainer`

- `EasyInstancePool _togglePool`

- `GameObject _panelLocked`

- `GameObject _textLocked`

- `Transform _panelChat`

- `RoguelikeChatController _chatPrefab`

- `Int32 m_cachedItemIndex`

- `TweenWrapper m_tween`

- `Boolean m_hasInit`

- `ChatSwitchDirection m_cachedDirection`

- `RoguelikeChatController m_chatView`

- `ArchiveChatController <controller>k__BackingField`


## Properties

- `ArchiveChatController controller`


## Methods

- `ArchiveChatController get_controller()`

- `Void set_controller(ArchiveChatController)`

- `Void _InitIfNot()`

- `Void _RefreshAllContent(Boolean)`

- `Void _RefreshChatPortraits(Boolean, List`1)`

- `Void _RenderFadeSwitchContents(ChatItemModel)`

- `Void OnNextBtnClick()`

- `Void OnPrevBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveChatListDataBinder : DataBinder`1
{
	private const Int32 CHAR_SLOT_NUM; // 0x0
	private const Single FADE_SWITCH_DUR; // 0x0
	private const Single FADE_RENDER_DELAY; // 0x0
	private CanvasGroup _panelFadeSwitch; // 0x20
	private ArchiveChatDetailItemView _viewDetail; // 0x28
	private RoguelikeTopicMonthSquadCharPortraitView _charPrefab; // 0x30
	private Transform _charContainer; // 0x38
	private EasyInstancePool _togglePool; // 0x40
	private GameObject _panelLocked; // 0x48
	private GameObject _textLocked; // 0x50
	private Transform _panelChat; // 0x58
	private RoguelikeChatController _chatPrefab; // 0x60
	private ListDict`2 m_cachedChatItems; // 0x68
	private Int32 m_cachedItemIndex; // 0x70
	private TweenWrapper m_tween; // 0x78
	private Boolean m_hasInit; // 0x80
	private ChatSwitchDirection m_cachedDirection; // 0x84
	private List`1 m_charPortraitViews; // 0x88
	private RoguelikeChatController m_chatView; // 0x90
	private ArchiveChatController <controller>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RefreshAllContent; // 0x20
	private static DelegateBridge __Hotfix0__RefreshChatPortraits; // 0x28
	private static DelegateBridge __Hotfix0__RenderFadeSwitchContents; // 0x30
	private static DelegateBridge __Hotfix0_OnNextBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_OnPrevBtnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private ArchiveChatController controller { get; set; }

	// RVA: 0x3043afc VA: 0x759565bafc
	private ArchiveChatController get_controller() { }
	// RVA: 0x30431e4 VA: 0x759565b1e4
	public Void set_controller(ArchiveChatController value) { }
	// RVA: 0x3043b64 VA: 0x759565bb64
	public override Void OnValueChanged(ChatProperty property) { }
	// RVA: 0x3043c38 VA: 0x759565bc38
	private Void _InitIfNot() { }
	// RVA: 0x3043e50 VA: 0x759565be50
	private Void _RefreshAllContent(Boolean isInit) { }
	// RVA: 0x3044130 VA: 0x759565c130
	private Void _RefreshChatPortraits(Boolean isInit, List`1 selectedCharIds) { }
	// RVA: 0x3044324 VA: 0x759565c324
	private Void _RenderFadeSwitchContents(ChatItemModel selectedItem) { }
	// RVA: 0x304460c VA: 0x759565c60c
	public Void OnNextBtnClick() { }
	// RVA: 0x304474c VA: 0x759565c74c
	public Void OnPrevBtnClick() { }
	// RVA: 0x304488c VA: 0x759565c88c
	public Void .ctor() { }
}
```