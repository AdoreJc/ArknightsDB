# HideArrowIfScrollAtLastItem

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _lastItemCnt`

- `GameObject _horizontalArrow`

- `GameObject _verticalArrow`

- `Boolean m_isInited`

- `Wrapper m_scrollRect`

- `Boolean m_isScrollVertical`

- `Boolean m_isScrollHorizontal`

- `Param m_cachedParam`

- `Single m_cachedVerThreshold`

- `Single m_cachedHorThreshold`


## Methods

- `Void SetParam(Param)`

- `Void _InitIfNot()`

- `Void _OnValueChanged(Vector2)`

- `Void _UpdateArrowState(Vector2)`

- `Void _RecalculateThreshold()`

- `Single _CalculateAxisThreshold(Single, Int32, Single)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class HideArrowIfScrollAtLastItem : MonoBehaviour, IHotfixable
{
	private Int32 _lastItemCnt; // 0x18
	private GameObject _horizontalArrow; // 0x20
	private GameObject _verticalArrow; // 0x28
	private Boolean m_isInited; // 0x30
	private Wrapper m_scrollRect; // 0x38
	private Boolean m_isScrollVertical; // 0x40
	private Boolean m_isScrollHorizontal; // 0x41
	private Param m_cachedParam; // 0x44
	private Single m_cachedVerThreshold; // 0x50
	private Single m_cachedHorThreshold; // 0x54
	private static DelegateBridge __Hotfix0_SetParam; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__UpdateArrowState; // 0x18
	private static DelegateBridge __Hotfix0__RecalculateThreshold; // 0x20
	private static DelegateBridge __Hotfix0__CalculateAxisThreshold; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x21c46e0 VA: 0x75947dc6e0
	public Void SetParam(Param param) { }
	// RVA: 0x21c4864 VA: 0x75947dc864
	private Void _InitIfNot() { }
	// RVA: 0x21c49b0 VA: 0x75947dc9b0
	private Void _OnValueChanged(Vector2 size) { }
	// RVA: 0x21c4a3c VA: 0x75947dca3c
	private Void _UpdateArrowState(Vector2 size) { }
	// RVA: 0x21c4784 VA: 0x75947dc784
	private Void _RecalculateThreshold() { }
	// RVA: 0x21c4b54 VA: 0x75947dcb54
	private Single _CalculateAxisThreshold(Single axisLength, Int32 itemCnt, Single itemSize) { }
	// RVA: 0x21c4c4c VA: 0x75947dcc4c
	private Void Start() { }
	// RVA: 0x21c4ce0 VA: 0x75947dcce0
	public Void .ctor() { }
}
```