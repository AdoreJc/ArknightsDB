# UIAutoSlideRect

**Namespace:** `Torappu.UI`


## Fields

- `Single _horizontalSpeed`

- `Single _verticalSpeed`

- `Single _beginWaitingTime`

- `Single _endWaitingTime`

- `RectTransform _referenceRectTransform`

- `Single _textFadeDuration`

- `Boolean _selfDrive`

- `RectTransform m_rectTrans`

- `Vector2 m_startPos`

- `Coroutine m_movingCoroutine`

- `Vector2 m_moveDistance`

- `Vector2 m_sizeCache`

- `CanvasGroup m_optionalAlphaHandler`

- `Int32 counter`


## Methods

- `CanvasGroup _EnsureAlphaHandler()`

- `Void Awake()`

- `Void Update()`

- `Void OnDisable()`

- `Void _TryStopCoroutine()`

- `Vector2 _CalculateMoveDistance()`

- `IEnumerator _MovingCoroutine()`

- `Void ResetSliding()`

- `Single _MoveDistance(Single, Single, Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAutoSlideRect : MonoBehaviour, IHotfixable
{
	private const Single MOVE_THRESHOLD; // 0x0
	private Single _horizontalSpeed; // 0x18
	private Single _verticalSpeed; // 0x1c
	private Single _beginWaitingTime; // 0x20
	private Single _endWaitingTime; // 0x24
	private RectTransform _referenceRectTransform; // 0x28
	private Single _textFadeDuration; // 0x30
	private Boolean _selfDrive; // 0x34
	private RectTransform m_rectTrans; // 0x38
	private Vector2 m_startPos; // 0x40
	private Coroutine m_movingCoroutine; // 0x48
	private Vector2 m_moveDistance; // 0x50
	private Vector2 m_sizeCache; // 0x58
	private CanvasGroup m_optionalAlphaHandler; // 0x60
	private Int32 counter; // 0x68
	private static DelegateBridge __Hotfix0__EnsureAlphaHandler; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0__TryStopCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__CalculateMoveDistance; // 0x28
	private static DelegateBridge __Hotfix0__MovingCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_ResetSliding; // 0x38
	private static DelegateBridge __Hotfix0__MoveDistance; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x21eaf04 VA: 0x7594802f04
	private CanvasGroup _EnsureAlphaHandler() { }
	// RVA: 0x21eb08c VA: 0x759480308c
	private Void Awake() { }
	// RVA: 0x21eb1dc VA: 0x75948031dc
	private Void Update() { }
	// RVA: 0x21eb418 VA: 0x7594803418
	private Void OnDisable() { }
	// RVA: 0x21eb4b4 VA: 0x75948034b4
	private Void _TryStopCoroutine() { }
	// RVA: 0x21eb548 VA: 0x7594803548
	private Vector2 _CalculateMoveDistance() { }
	// RVA: 0x21eb660 VA: 0x7594803660
	private IEnumerator _MovingCoroutine() { }
	// RVA: 0x21eb37c VA: 0x759480337c
	public Void ResetSliding() { }
	// RVA: 0x21eb734 VA: 0x7594803734
	private Single _MoveDistance(Single targetDistance, Single cur, Single min, Single max) { }
	// RVA: 0x21eb800 VA: 0x7594803800
	public Void .ctor() { }
}
```