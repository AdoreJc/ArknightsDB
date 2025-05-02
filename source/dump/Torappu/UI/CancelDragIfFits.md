# CancelDragIfFits

**Namespace:** `Torappu.UI`


## Fields

- `Single CONST_DELTA`

- `GameObject _disableTargetIfCancel`

- `GameObject _topArrow`

- `GameObject _downArrow`

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `Boolean m_isLocked`

- `Wrapper m_scrollRect`

- `Boolean m_originScrollVertical`

- `Boolean m_originScrollHorizontal`

- `Boolean m_isInited`


## Properties

- `Boolean isLocked`


## Methods

- `Void _InitIfNot()`

- `Boolean get_isLocked()`

- `Void set_isLocked(Boolean)`

- `Void UpdateLockState()`

- `Void _UpdateLockState()`

- `Void _UpdateArrowState(Vector2)`

- `Void _OnValueChanged(Vector2)`

- `Void _OnContentLayoutRebuilt()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CancelDragIfFits : MonoBehaviour, IHotfixable
{
	private Single CONST_DELTA; // 0x18
	private GameObject _disableTargetIfCancel; // 0x20
	private GameObject _topArrow; // 0x28
	private GameObject _downArrow; // 0x30
	private GameObject _leftArrow; // 0x38
	private GameObject _rightArrow; // 0x40
	private Boolean m_isLocked; // 0x48
	private Wrapper m_scrollRect; // 0x50
	private Boolean m_originScrollVertical; // 0x58
	private Boolean m_originScrollHorizontal; // 0x59
	private Boolean m_isInited; // 0x5a
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x8
	private static DelegateBridge __Hotfix0_set_isLocked; // 0x10
	private static DelegateBridge __Hotfix0_UpdateLockState; // 0x18
	private static DelegateBridge __Hotfix0__UpdateLockState; // 0x20
	private static DelegateBridge __Hotfix0__UpdateArrowState; // 0x28
	private static DelegateBridge __Hotfix0__OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__OnContentLayoutRebuilt; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean isLocked { get; set; }

	// RVA: 0x21c0dec VA: 0x75947d8dec
	private Void _InitIfNot() { }
	// RVA: 0x21c100c VA: 0x75947d900c
	public Boolean get_isLocked() { }
	// RVA: 0x21c1074 VA: 0x75947d9074
	private Void set_isLocked(Boolean value) { }
	// RVA: 0x21c1208 VA: 0x75947d9208
	public Void UpdateLockState() { }
	// RVA: 0x21c1270 VA: 0x75947d9270
	private Void _UpdateLockState() { }
	// RVA: 0x21c13c0 VA: 0x75947d93c0
	private Void _UpdateArrowState(Vector2 size) { }
	// RVA: 0x21c153c VA: 0x75947d953c
	private Void _OnValueChanged(Vector2 size) { }
	// RVA: 0x21c15d0 VA: 0x75947d95d0
	private Void _OnContentLayoutRebuilt() { }
	// RVA: 0x21c1690 VA: 0x75947d9690
	private Void Start() { }
	// RVA: 0x21c1724 VA: 0x75947d9724
	public Void .ctor() { }
}
```