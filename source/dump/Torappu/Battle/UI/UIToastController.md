# UIToastController

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _tweenDuration`

- `UIToastSubPanel _infoPanel`

- `UIToastSubPanel _enemyPanel`

- `Boolean _ignoreTimeScale`

- `Single m_curShowTime`

- `Single m_curLastTime`

- `Int32 m_idCounter`

- `RectTransform m_rectTransform`

- `Vector2 m_originAnchorPos`

- `Tweener m_tweener`

- `UIToastSubPanel m_lastSubPanel`

- `ToastState <state>k__BackingField`


## Properties

- `ToastState state`

- `Single progress`

- `RectTransform rectTransform`


## Methods

- `ToastState get_state()`

- `Void set_state(ToastState)`

- `Single get_progress()`

- `RectTransform get_rectTransform()`

- `Int32 Show(Options, Boolean)`

- `IEnumerator _ShowInternal(Options, Boolean)`

- `Void SetPaused(Boolean)`

- `Void Hide(Boolean)`

- `Void Hide(Int32, Boolean)`

- `Void OnDestroy()`

- `Void OnInit()`

- `Void AttachExtraSubPanel(UIToastSubPanel, ToastType)`

- `Void OnUIStateChanged(IUIStateNode)`

- `UIToastSubPanel _GetSubPanel(ToastType)`

- `Void _PlaySoundEffect(SeType)`

- `Void _ResetAll()`

- `Void _HideInternal(Int32, Boolean)`

- `Void Update()`

- `Boolean <_ShowInternal>b__26_0()`

- `Void <_ShowInternal>b__26_1()`

- `Void <_HideInternal>b__37_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIToastController : MonoBehaviour, IHotfixable
{
	private Single _tweenDuration; // 0x18
	private UIToastSubPanel _infoPanel; // 0x20
	private UIToastSubPanel _enemyPanel; // 0x28
	private Boolean _ignoreTimeScale; // 0x30
	private Single m_curShowTime; // 0x34
	private Single m_curLastTime; // 0x38
	private Int32 m_idCounter; // 0x3c
	private RectTransform m_rectTransform; // 0x40
	private Vector2 m_originAnchorPos; // 0x48
	private Dictionary`2 m_subPanels; // 0x50
	private Tweener m_tweener; // 0x58
	private UIToastSubPanel m_lastSubPanel; // 0x60
	private ToastState <state>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_get_progress; // 0x10
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x18
	private static DelegateBridge __Hotfix0_Show; // 0x20
	private static DelegateBridge __Hotfix0__ShowInternal; // 0x28
	private static DelegateBridge __Hotfix0_SetPaused; // 0x30
	private static DelegateBridge __Hotfix0_Hide; // 0x38
	private static DelegateBridge __Hotfix1_Hide; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0_OnInit; // 0x50
	private static DelegateBridge __Hotfix0_AttachExtraSubPanel; // 0x58
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x60
	private static DelegateBridge __Hotfix0__GetSubPanel; // 0x68
	private static DelegateBridge __Hotfix0__PlaySoundEffect; // 0x70
	private static DelegateBridge __Hotfix0__ResetAll; // 0x78
	private static DelegateBridge __Hotfix0__HideInternal; // 0x80
	private static DelegateBridge __Hotfix0_Update; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public ToastState state { get; set; }
	protected Single progress { get; }
	protected RectTransform rectTransform { get; }

	// RVA: 0x20442c8 VA: 0x759465c2c8
	public ToastState get_state() { }
	// RVA: 0x2044330 VA: 0x759465c330
	private Void set_state(ToastState value) { }
	// RVA: 0x20443ac VA: 0x759465c3ac
	protected Single get_progress() { }
	// RVA: 0x204448c VA: 0x759465c48c
	protected RectTransform get_rectTransform() { }
	// RVA: 0x2044564 VA: 0x759465c564
	public Int32 Show(Options options, Boolean needHide) { }
	// RVA: 0x2044744 VA: 0x759465c744
	private IEnumerator _ShowInternal(Options options, Boolean needHide) { }
	// RVA: 0x2044880 VA: 0x759465c880
	public Void SetPaused(Boolean value) { }
	// RVA: 0x2043cac VA: 0x759465bcac
	public Void Hide(Boolean withAnimation) { }
	// RVA: 0x204495c VA: 0x759465c95c
	public Void Hide(Int32 popupId, Boolean withAnimation) { }
	// RVA: 0x2044c54 VA: 0x759465cc54
	private Void OnDestroy() { }
	// RVA: 0x2044cc0 VA: 0x759465ccc0
	public Void OnInit() { }
	// RVA: 0x2044eac VA: 0x759465ceac
	public Void AttachExtraSubPanel(UIToastSubPanel subPanel, ToastType toastType) { }
	// RVA: 0x2044f94 VA: 0x759465cf94
	public Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x2045024 VA: 0x759465d024
	private UIToastSubPanel _GetSubPanel(ToastType popupType) { }
	// RVA: 0x20451c8 VA: 0x759465d1c8
	private Void _PlaySoundEffect(SeType seType) { }
	// RVA: 0x2044d84 VA: 0x759465cd84
	private Void _ResetAll() { }
	// RVA: 0x2044a10 VA: 0x759465ca10
	private Void _HideInternal(Int32 popupId, Boolean force) { }
	// RVA: 0x2045304 VA: 0x759465d304
	private Void Update() { }
	// RVA: 0x2045428 VA: 0x759465d428
	public Void .ctor() { }
	// RVA: 0x2045500 VA: 0x759465d500
	private Boolean <_ShowInternal>b__26_0() { }
	// RVA: 0x2045518 VA: 0x759465d518
	private Void <_ShowInternal>b__26_1() { }
	// RVA: 0x2045520 VA: 0x759465d520
	private Void <_HideInternal>b__37_0() { }
}
```