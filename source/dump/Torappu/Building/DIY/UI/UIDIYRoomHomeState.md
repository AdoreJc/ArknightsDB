# UIDIYRoomHomeState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `CanvasGroup _canvasGroup`

- `UIRoomThemeSpriteHub _themeSpriteHub`

- `UIRoomThemeIconSpriteHub _themeIconSpriteHub`

- `Image _bgImage`

- `Image _themeImage`

- `Text _nameLabel`

- `Text _descLabel`

- `GameObject _levelupHint`

- `RoomSlotModel m_currentRoom`


## Methods

- `Void SetupView(Argument)`

- `Void ActuallyShow()`

- `Void OnLevelupButtonPressed()`

- `Void OnCancelButtonPressed()`

- `Void <HideCoroutine>b__13_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class UIDIYRoomHomeState : UIPopupState
{
	private CanvasGroup _canvasGroup; // 0x60
	private UIRoomThemeSpriteHub _themeSpriteHub; // 0x68
	private UIRoomThemeIconSpriteHub _themeIconSpriteHub; // 0x70
	private Image _bgImage; // 0x78
	private Image _themeImage; // 0x80
	private Text _nameLabel; // 0x88
	private Text _descLabel; // 0x90
	private GameObject _levelupHint; // 0x98
	private RoomSlotModel m_currentRoom; // 0xa0
	private static DelegateBridge __Hotfix0_SetupView; // 0x0
	private static DelegateBridge __Hotfix0_ActuallyShow; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x20
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge __Hotfix0_OnLevelupButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0_OnCancelButtonPressed; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x383ac60 VA: 0x7595e52c60
	public Void SetupView(Argument arg) { }
	// RVA: 0x383af98 VA: 0x7595e52f98
	public Void ActuallyShow() { }
	// RVA: 0x383b02c VA: 0x7595e5302c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x383b1a4 VA: 0x7595e531a4
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x383b31c VA: 0x7595e5331c
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x383b428 VA: 0x7595e53428
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x383b534 VA: 0x7595e53534
	public override IStateBean GetCacheBean() { }
	// RVA: 0x383b598 VA: 0x7595e53598
	public Void OnLevelupButtonPressed() { }
	// RVA: 0x383b64c VA: 0x7595e5364c
	public Void OnCancelButtonPressed() { }
	// RVA: 0x383b700 VA: 0x7595e53700
	public Void .ctor() { }
	// RVA: 0x383b770 VA: 0x7595e53770
	private Void <HideCoroutine>b__13_0() { }
}
```