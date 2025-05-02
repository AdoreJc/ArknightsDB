# NameCardDisplayPage

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Transform _container`

- `CanvasGroup _closeButton`

- `UIRenderTextureImage _blurBg`

- `NameCardV2View m_viewObj`

- `NameCardV2Property m_property`

- `Boolean m_hasCardInited`

- `Coroutine m_coroutine`

- `Boolean m_cachedShowDetail`


## Methods

- `Void _ApplyDataFriend(FriendDataWithNameCard)`

- `Void _ApplyDataSelf()`

- `IEnumerator _FadeInCloseButtonObj()`

- `IEnumerator _FadeOutCloseButtonObj()`

- `Void CloseNameCard()`

- `Void _InitNameCardIfNot()`

- `Void _SaveStatus()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SwitchOperatorStyle(String)`

- `Void _SwitchAssistStyle(String)`

- `Void _SwitchEquipStyle(String)`

- `Void _CrossAppShare(String, Int32, Boolean)`

- `Void _ExtendNameCard(Boolean)`

- `Void _CloseButtonFadeIn()`

- `IEnumerator <>n__0(Boolean)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardDisplayPage : UIPage, IValueMsgReceiver
{
	public const Int32 SWITCH_OPERATOR_STYLE; // 0x0
	public const Int32 SWITCH_ASSIST_STYLE; // 0x0
	public const Int32 CROSS_APP_SHARE; // 0x0
	public const Int32 CROSS_APP_SHARE_SIMPLE; // 0x0
	public const Int32 EXTEND_NAMECARD; // 0x0
	public const Int32 CLOSE_BTN_FADE_IN; // 0x0
	public const Int32 SWITCH_EQUIP_MODULE_STYLE; // 0x0
	private const Int32 FADE_IN_TIME; // 0x0
	private const Int32 CLOSE_BUTTON_HIDE_TIME; // 0x0
	private Transform _container; // 0xd0
	private CanvasGroup _closeButton; // 0xd8
	private UIRenderTextureImage _blurBg; // 0xe0
	private NameCardV2View m_viewObj; // 0xe8
	private NameCardV2Property m_property; // 0xf0
	private Boolean m_hasCardInited; // 0xf8
	private Coroutine m_coroutine; // 0x100
	private Boolean m_cachedShowDetail; // 0x108
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__ApplyDataFriend; // 0x10
	private static DelegateBridge __Hotfix0__ApplyDataSelf; // 0x18
	private static DelegateBridge __Hotfix0__FadeInCloseButtonObj; // 0x20
	private static DelegateBridge __Hotfix0__FadeOutCloseButtonObj; // 0x28
	private static DelegateBridge __Hotfix0_CloseNameCard; // 0x30
	private static DelegateBridge __Hotfix0__InitNameCardIfNot; // 0x38
	private static DelegateBridge __Hotfix0__SaveStatus; // 0x40
	private static DelegateBridge __Hotfix0_OnMessage; // 0x48
	private static DelegateBridge __Hotfix0__SwitchOperatorStyle; // 0x50
	private static DelegateBridge __Hotfix0__SwitchAssistStyle; // 0x58
	private static DelegateBridge __Hotfix0__SwitchEquipStyle; // 0x60
	private static DelegateBridge __Hotfix0__CrossAppShare; // 0x68
	private static DelegateBridge __Hotfix0__ExtendNameCard; // 0x70
	private static DelegateBridge __Hotfix0__CloseButtonFadeIn; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x28abdd8 VA: 0x7594ec3dd8
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x28abf20 VA: 0x7594ec3f20
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x28ac010 VA: 0x7594ec4010
	private Void _ApplyDataFriend(FriendDataWithNameCard viewModel) { }
	// RVA: 0x28ac3a0 VA: 0x7594ec43a0
	private Void _ApplyDataSelf() { }
	// RVA: 0x28ac4bc VA: 0x7594ec44bc
	private IEnumerator _FadeInCloseButtonObj() { }
	// RVA: 0x28ac590 VA: 0x7594ec4590
	private IEnumerator _FadeOutCloseButtonObj() { }
	// RVA: 0x28ac664 VA: 0x7594ec4664
	public Void CloseNameCard() { }
	// RVA: 0x28ac12c VA: 0x7594ec412c
	private Void _InitNameCardIfNot() { }
	// RVA: 0x28ac718 VA: 0x7594ec4718
	private Void _SaveStatus() { }
	// RVA: 0x28acb08 VA: 0x7594ec4b08
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28acca4 VA: 0x7594ec4ca4
	private Void _SwitchOperatorStyle(String moduleId) { }
	// RVA: 0x28acd8c VA: 0x7594ec4d8c
	private Void _SwitchAssistStyle(String moduleId) { }
	// RVA: 0x28ad21c VA: 0x7594ec521c
	private Void _SwitchEquipStyle(String moduleId) { }
	// RVA: 0x28ace74 VA: 0x7594ec4e74
	private Void _CrossAppShare(String skinId, Int32 skinTmpl, Boolean isDetail) { }
	// RVA: 0x28ad10c VA: 0x7594ec510c
	private Void _ExtendNameCard(Boolean isExtend) { }
	// RVA: 0x28ac2c4 VA: 0x7594ec42c4
	private Void _CloseButtonFadeIn() { }
	// RVA: 0x28ad304 VA: 0x7594ec5304
	public Void .ctor() { }
	// RVA: 0x28ad3b4 VA: 0x7594ec53b4
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x28ad3c0 VA: 0x7594ec53c0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x28ad3c8 VA: 0x7594ec53c8
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
}
```