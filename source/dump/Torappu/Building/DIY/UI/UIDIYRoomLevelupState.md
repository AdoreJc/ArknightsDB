# UIDIYRoomLevelupState

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `CanvasGroup _canvasGroup`

- `RectTransform _infoRoot`

- `GameObject _infoProto`

- `RectTransform _costRoot`

- `GameObject _costProto`

- `RectTransform _furnitureRoot`

- `GameObject _furnitureProto`

- `GameObject _cannotLevelupPanel`

- `Image _bgImage`

- `UIRoomThemeSpriteHub _bgSpriteHub`

- `GameObject _conditionPanel`

- `UIComplexRoomLevelView _conditionTargetLevelView`

- `Tweener m_showTween`

- `Tweener m_hideTween`

- `RoomSlotModel m_currentRoom`


## Methods

- `Void SetupView(Argument, Func`2)`

- `Void OnLevelupButtonPressed()`

- `Void OnCancelButtonPressed()`

- `Single _GetAlpha()`

- `Void Awake()`

- `Void <HideCoroutine>b__18_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class UIDIYRoomLevelupState : UIPopupState
{
	private CanvasGroup _canvasGroup; // 0x60
	private RectTransform _infoRoot; // 0x68
	private GameObject _infoProto; // 0x70
	private RectTransform _costRoot; // 0x78
	private GameObject _costProto; // 0x80
	private RectTransform _furnitureRoot; // 0x88
	private GameObject _furnitureProto; // 0x90
	private GameObject _cannotLevelupPanel; // 0x98
	private Image _bgImage; // 0xa0
	private UIRoomThemeSpriteHub _bgSpriteHub; // 0xa8
	private GameObject _conditionPanel; // 0xb0
	private UIComplexRoomLevelView _conditionTargetLevelView; // 0xb8
	private Tweener m_showTween; // 0xc0
	private Tweener m_hideTween; // 0xc8
	private RoomSlotModel m_currentRoom; // 0xd0
	private static DelegateBridge __Hotfix0_SetupView; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OnLevelupButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0_OnCancelButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0__GetAlpha; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x383babc VA: 0x7595e53abc
	public Void SetupView(Argument arg, Func`2 onOK) { }
	// RVA: 0x383c064 VA: 0x7595e54064
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x383c1dc VA: 0x7595e541dc
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x383c354 VA: 0x7595e54354
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x383c460 VA: 0x7595e54460
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x383c56c VA: 0x7595e5456c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x383c5d0 VA: 0x7595e545d0
	public Void OnLevelupButtonPressed() { }
	// RVA: 0x383c684 VA: 0x7595e54684
	public Void OnCancelButtonPressed() { }
	// RVA: 0x383c738 VA: 0x7595e54738
	private Single _GetAlpha() { }
	// RVA: 0x383c7ac VA: 0x7595e547ac
	private Void Awake() { }
	// RVA: 0x383c810 VA: 0x7595e54810
	public Void .ctor() { }
	// RVA: 0x383c880 VA: 0x7595e54880
	private Void <HideCoroutine>b__18_0() { }
}
```