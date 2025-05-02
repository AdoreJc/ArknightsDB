# NameCardSkinChangeState

**Namespace:** `Torappu.UI.Friend`


## Fields

- `RectTransform _rectCancel`

- `NameCardSkinChangeView _changeView`

- `NameCardSkinTmplChangeView _skinTmplChangeViewPrefab`

- `RectTransform _skinTmplChangeViewContent`

- `Transform _nameCardContainer`

- `Single _nameCardScale`

- `Boolean m_isInited`

- `NameCardSkinTmplChangeView m_skinTmplChangeView`

- `NameCardV2View m_nameCardView`

- `NameCardSkinChangeStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `String _ConsumeRoutedNameCardSkinId()`

- `Void _HandleSelectSkin(String)`

- `Void _HandleToChangeSkinTmpl(String)`

- `Void _HandleHideChangeSkinTmpl()`

- `Void _HandleSelectSkinTmpl(Int32)`

- `Void _HandleConfirmSkinTmpl(ValueBundle)`

- `Void _HandleCancelSkinTmpl()`

- `Void OnConfirmBtnClick()`

- `Void CloseState()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <_HandleConfirmSkinTmpl>b__24_0(EditNameCardResponse)`

- `Void <OnConfirmBtnClick>b__26_0(EditNameCardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinChangeState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 SELECT_SKIN; // 0x0
	public const Int32 TO_CHANGE_SKIN_TMPL; // 0x0
	public const Int32 HIDE_CHANGE_SKIN_TMPL; // 0x0
	public const Int32 SELECT_SKIN_TMPL; // 0x0
	public const Int32 CONFIRM_SKIN_TMPL; // 0x0
	public const Int32 CANCEL_SKIN_TMPL; // 0x0
	private RectTransform _rectCancel; // 0x70
	private NameCardSkinChangeView _changeView; // 0x78
	private NameCardSkinTmplChangeView _skinTmplChangeViewPrefab; // 0x80
	private RectTransform _skinTmplChangeViewContent; // 0x88
	private Transform _nameCardContainer; // 0x90
	private Single _nameCardScale; // 0x98
	private Boolean m_isInited; // 0x9c
	private NameCardSkinTmplChangeView m_skinTmplChangeView; // 0xa0
	private NameCardV2View m_nameCardView; // 0xa8
	private NameCardSkinChangeStateBean m_stateBean; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__ConsumeRoutedNameCardSkinId; // 0x18
	private static DelegateBridge __Hotfix0__HandleSelectSkin; // 0x20
	private static DelegateBridge __Hotfix0__HandleToChangeSkinTmpl; // 0x28
	private static DelegateBridge __Hotfix0__HandleHideChangeSkinTmpl; // 0x30
	private static DelegateBridge __Hotfix0__HandleSelectSkinTmpl; // 0x38
	private static DelegateBridge __Hotfix0__HandleConfirmSkinTmpl; // 0x40
	private static DelegateBridge __Hotfix0__HandleCancelSkinTmpl; // 0x48
	private static DelegateBridge __Hotfix0_OnConfirmBtnClick; // 0x50
	private static DelegateBridge __Hotfix0_CloseState; // 0x58
	private static DelegateBridge __Hotfix0_OnMessage; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x28b8644 VA: 0x7594ed0644
	private Void _InitIfNot() { }
	// RVA: 0x28b8954 VA: 0x7594ed0954
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28b89bc VA: 0x7594ed09bc
	protected override Void OnEnter() { }
	// RVA: 0x28b8aa0 VA: 0x7594ed0aa0
	private String _ConsumeRoutedNameCardSkinId() { }
	// RVA: 0x28b8d68 VA: 0x7594ed0d68
	private Void _HandleSelectSkin(String selectedId) { }
	// RVA: 0x28b8fb4 VA: 0x7594ed0fb4
	private Void _HandleToChangeSkinTmpl(String skinId) { }
	// RVA: 0x28b9130 VA: 0x7594ed1130
	private Void _HandleHideChangeSkinTmpl() { }
	// RVA: 0x28b9258 VA: 0x7594ed1258
	private Void _HandleSelectSkinTmpl(Int32 skinTmpl) { }
	// RVA: 0x28b93b4 VA: 0x7594ed13b4
	private Void _HandleConfirmSkinTmpl(ValueBundle vb) { }
	// RVA: 0x28b9610 VA: 0x7594ed1610
	private Void _HandleCancelSkinTmpl() { }
	// RVA: 0x28b9680 VA: 0x7594ed1680
	public Void OnConfirmBtnClick() { }
	// RVA: 0x28b99d4 VA: 0x7594ed19d4
	public Void CloseState() { }
	// RVA: 0x28b9ae8 VA: 0x7594ed1ae8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28b9c2c VA: 0x7594ed1c2c
	public Void .ctor() { }
	// RVA: 0x28b9dbc VA: 0x7594ed1dbc
	private Void <_HandleConfirmSkinTmpl>b__24_0(EditNameCardResponse response) { }
	// RVA: 0x28b9f54 VA: 0x7594ed1f54
	private Void <OnConfirmBtnClick>b__26_0(EditNameCardResponse response) { }
	// RVA: 0x28b9f58 VA: 0x7594ed1f58
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```