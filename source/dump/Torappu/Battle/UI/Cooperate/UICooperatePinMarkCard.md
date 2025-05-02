# UICooperatePinMarkCard

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Transform _dummy`

- `ScrollRect _scrollRect`

- `NonDrawingGraphic _pinMarkCollider`

- `UICooperateFortressEdgePanel _fortressEdgePanel`

- `UIAnimationLocation _buttonWrapper`

- `RectTransform _inCooldown`

- `Text _inCooldownText`

- `RectTransform _inMark`

- `Single m_interval`

- `Int32 m_intervalTime`

- `Single m_cooldown`

- `PeriodicTimer m_intervalTimer`

- `PeriodicTimer m_cooldownTimer`

- `Int32 m_curTime`

- `Tween m_animTween`

- `Boolean m_isCooldown`

- `Int32 <currentPointerId>k__BackingField`


## Properties

- `CooperateGameMode mode`

- `Int32 currentPointerId`


## Methods

- `CooperateGameMode get_mode()`

- `Int32 get_currentPointerId()`

- `Void set_currentPointerId(Int32)`

- `Void OnDrag(BaseEventData)`

- `Void OnBeginDrag(BaseEventData)`

- `Void OnEndDrag(BaseEventData)`

- `Transform CreateDummy()`

- `Void DestroyDummy()`

- `Void OnInit()`

- `Void OnFixedUpdate(FP)`

- `Void _UpdateData(FP)`

- `Void _UpdateCooldown(FP)`

- `Void _SetCooldownState(Boolean)`

- `Void OnReceivePinMark(Object)`

- `PeriodicTimer _NewPinMarkTimer()`

- `Boolean OnBeforeCreateEffect()`

- `Void CreateEffectMySide(Tile, Int32)`

- `Void PlayCardTween()`

- `Void SetTweenMark()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperatePinMarkCard : MonoBehaviour, IHotfixable
{
	private const String COOL_DOWN_FORMAT; // 0x0
	private Transform _dummy; // 0x18
	private ScrollRect _scrollRect; // 0x20
	private NonDrawingGraphic _pinMarkCollider; // 0x28
	private UICooperateFortressEdgePanel _fortressEdgePanel; // 0x30
	private UIAnimationLocation _buttonWrapper; // 0x38
	private RectTransform _inCooldown; // 0x48
	private Text _inCooldownText; // 0x50
	private RectTransform _inMark; // 0x58
	private Single m_interval; // 0x60
	private Int32 m_intervalTime; // 0x64
	private Single m_cooldown; // 0x68
	private PeriodicTimer m_intervalTimer; // 0x70
	private PeriodicTimer m_cooldownTimer; // 0x78
	private Int32 m_curTime; // 0x80
	private Tween m_animTween; // 0x88
	private Boolean m_isCooldown; // 0x90
	private readonly List`1 m_reusablePinTimerList; // 0x98
	private readonly List`1 m_pinTimerList; // 0xa0
	private readonly ListDict`2 m_pinEffectList; // 0xa8
	private readonly List`1 m_othersPinTimerList; // 0xb0
	private readonly ListDict`2 m_othersPinEffectList; // 0xb8
	private readonly ListDict`2 m_othersPinOuter; // 0xc0
	private readonly ListDict`2 m_othersPinOuterEnemy; // 0xc8
	private Int32 <currentPointerId>k__BackingField; // 0xd0
	private static DelegateBridge __Hotfix0_get_mode; // 0x0
	private static DelegateBridge __Hotfix0_get_currentPointerId; // 0x8
	private static DelegateBridge __Hotfix0_set_currentPointerId; // 0x10
	private static DelegateBridge __Hotfix0_OnDrag; // 0x18
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x20
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x28
	private static DelegateBridge __Hotfix0_CreateDummy; // 0x30
	private static DelegateBridge __Hotfix0_DestroyDummy; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0_OnFixedUpdate; // 0x48
	private static DelegateBridge __Hotfix0__UpdateData; // 0x50
	private static DelegateBridge __Hotfix0__UpdateCooldown; // 0x58
	private static DelegateBridge __Hotfix0__SetCooldownState; // 0x60
	private static DelegateBridge __Hotfix0_OnReceivePinMark; // 0x68
	private static DelegateBridge __Hotfix0__NewPinMarkTimer; // 0x70
	private static DelegateBridge __Hotfix0_OnBeforeCreateEffect; // 0x78
	private static DelegateBridge __Hotfix0_CreateEffectMySide; // 0x80
	private static DelegateBridge __Hotfix0_PlayCardTween; // 0x88
	private static DelegateBridge __Hotfix0_SetTweenMark; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	private CooperateGameMode mode { get; }
	public Int32 currentPointerId { get; set; }

	// RVA: 0x20e94d8 VA: 0x75947014d8
	private CooperateGameMode get_mode() { }
	// RVA: 0x20e95b4 VA: 0x75947015b4
	public Int32 get_currentPointerId() { }
	// RVA: 0x20e961c VA: 0x759470161c
	public Void set_currentPointerId(Int32 value) { }
	// RVA: 0x20e9698 VA: 0x7594701698
	public Void OnDrag(BaseEventData eventData) { }
	// RVA: 0x20e9774 VA: 0x7594701774
	public Void OnBeginDrag(BaseEventData eventData) { }
	// RVA: 0x20e98c0 VA: 0x75947018c0
	public Void OnEndDrag(BaseEventData eventData) { }
	// RVA: 0x20e9ba4 VA: 0x7594701ba4
	public Transform CreateDummy() { }
	// RVA: 0x20e9c30 VA: 0x7594701c30
	public Void DestroyDummy() { }
	// RVA: 0x20e9cb4 VA: 0x7594701cb4
	public Void OnInit() { }
	// RVA: 0x20e9f90 VA: 0x7594701f90
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x20ea070 VA: 0x7594702070
	private Void _UpdateData(FP deltaTime) { }
	// RVA: 0x20ea5d0 VA: 0x75947025d0
	public Void _UpdateCooldown(FP deltaTime) { }
	// RVA: 0x20ea7b4 VA: 0x75947027b4
	private Void _SetCooldownState(Boolean isInCooldown) { }
	// RVA: 0x20ea92c VA: 0x759470292c
	public Void OnReceivePinMark(Object arg) { }
	// RVA: 0x20eaee0 VA: 0x7594702ee0
	private PeriodicTimer _NewPinMarkTimer() { }
	// RVA: 0x20eb004 VA: 0x7594703004
	public Boolean OnBeforeCreateEffect() { }
	// RVA: 0x20eb180 VA: 0x7594703180
	public Void CreateEffectMySide(Tile tile, Int32 type) { }
	// RVA: 0x20eb654 VA: 0x7594703654
	public Void PlayCardTween() { }
	// RVA: 0x20e99b8 VA: 0x75947019b8
	public Void SetTweenMark() { }
	// RVA: 0x20eb820 VA: 0x7594703820
	public Void .ctor() { }
}
```