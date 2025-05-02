# HideArrowIfScrollEnd

**Namespace:** `Torappu.UI`


## Fields

- `Single CONST_DELTA`

- `GameObject _topArrow`

- `GameObject _downArrow`

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `Boolean m_isInited`

- `Wrapper m_scrollRect`

- `Boolean m_isScrollVertical`

- `Boolean m_isScrollHorizontal`


## Methods

- `Void _InitIfNot()`

- `Void _OnValueChanged(Vector2)`

- `Void _UpdateArrowState(Vector2)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class HideArrowIfScrollEnd : MonoBehaviour, IHotfixable
{
	private Single CONST_DELTA; // 0x18
	private GameObject _topArrow; // 0x20
	private GameObject _downArrow; // 0x28
	private GameObject _leftArrow; // 0x30
	private GameObject _rightArrow; // 0x38
	private Boolean m_isInited; // 0x40
	private Wrapper m_scrollRect; // 0x48
	private Boolean m_isScrollVertical; // 0x50
	private Boolean m_isScrollHorizontal; // 0x51
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateArrowState; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x21c4d58 VA: 0x75947dcd58
	private Void _InitIfNot() { }
	// RVA: 0x21c4e9c VA: 0x75947dce9c
	private Void _OnValueChanged(Vector2 size) { }
	// RVA: 0x21c4f28 VA: 0x75947dcf28
	private Void _UpdateArrowState(Vector2 size) { }
	// RVA: 0x21c5064 VA: 0x75947dd064
	private Void Start() { }
	// RVA: 0x21c50f8 VA: 0x75947dd0f8
	public Void .ctor() { }
}
```