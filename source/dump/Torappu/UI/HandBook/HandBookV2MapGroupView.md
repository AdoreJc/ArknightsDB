# HandBookV2MapGroupView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapCardView _cardView`

- `HandBookV2MapLineView _lineView`

- `HandBookV2MapGroupBackView _backView`

- `HandBookV2SixLineView _sixLineView`

- `HandBookV2OtherForceView _otherForceView`

- `HandBookV2MapGroupLogoView _forceLogoView`

- `Transform _backContainer`

- `Transform _lineContainer`

- `Transform _sixLineContainer`

- `Transform _container`

- `CanvasGroup _alphaContainer`

- `UIHandBookCardEvent clickEvent`

- `UIStringEvent onForceClick`

- `HandBookV2MapGroupHolder holder`

- `Single m_maxX`

- `Single m_maxY`

- `Single m_minX`

- `Single m_minY`

- `Vector2 m_deltaVector2`


## Properties

- `Vector2 deltaVector`


## Methods

- `Vector2 get_deltaVector()`

- `Void _RenderLine(LineData)`

- `Void ApplyViewModel(HandBookV2GroupViewModel, String)`

- `IEnumerator OnHideEffect(Boolean)`

- `IEnumerator OnEnterEffect(Boolean)`

- `Boolean _IsForceAvail(String)`

- `Boolean _CanCharShowUp(HandBookV2GroupCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapGroupView : MonoBehaviour, IHotfixable
{
	private HandBookV2MapCardView _cardView; // 0x18
	private HandBookV2MapLineView _lineView; // 0x20
	private HandBookV2MapGroupBackView _backView; // 0x28
	private HandBookV2SixLineView _sixLineView; // 0x30
	private HandBookV2OtherForceView _otherForceView; // 0x38
	private HandBookV2MapGroupLogoView _forceLogoView; // 0x40
	private Transform _backContainer; // 0x48
	private Transform _lineContainer; // 0x50
	private Transform _sixLineContainer; // 0x58
	private Transform _container; // 0x60
	private CanvasGroup _alphaContainer; // 0x68
	public UIHandBookCardEvent clickEvent; // 0x70
	public UIStringEvent onForceClick; // 0x78
	public HandBookV2MapGroupHolder holder; // 0x80
	private Dictionary`2 m_cardView; // 0x88
	private Dictionary`2 m_lineView; // 0x90
	private Dictionary`2 m_backView; // 0x98
	private Dictionary`2 m_colorBlockList; // 0xa0
	private Dictionary`2 m_otherForceView; // 0xa8
	private Dictionary`2 m_forceLogoView; // 0xb0
	private Dictionary`2 m_sixLineGroupView; // 0xb8
	private Dictionary`2 m_forceId2AvailMap; // 0xc0
	private Single m_maxX; // 0xc8
	private Single m_maxY; // 0xcc
	private Single m_minX; // 0xd0
	private Single m_minY; // 0xd4
	private Vector2 m_deltaVector2; // 0xd8
	private static DelegateBridge __Hotfix0_get_deltaVector; // 0x0
	private static DelegateBridge __Hotfix0__RenderLine; // 0x8
	private static DelegateBridge __Hotfix0_ApplyViewModel; // 0x10
	private static DelegateBridge __Hotfix0_OnHideEffect; // 0x18
	private static DelegateBridge __Hotfix0_OnEnterEffect; // 0x20
	private static DelegateBridge __Hotfix0__IsForceAvail; // 0x28
	private static DelegateBridge __Hotfix0__CanCharShowUp; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Vector2 deltaVector { get; }

	// RVA: 0x2ed4eb8 VA: 0x75954eceb8
	public Vector2 get_deltaVector() { }
	// RVA: 0x2ed561c VA: 0x75954ed61c
	private Void _RenderLine(LineData lineData) { }
	// RVA: 0x2ed4360 VA: 0x75954ec360
	public Void ApplyViewModel(HandBookV2GroupViewModel viewModel, String mainForce) { }
	// RVA: 0x2ed4df0 VA: 0x75954ecdf0
	public IEnumerator OnHideEffect(Boolean isScale) { }
	// RVA: 0x2ed4f1c VA: 0x75954ecf1c
	public IEnumerator OnEnterEffect(Boolean isScale) { }
	// RVA: 0x2ed5ba0 VA: 0x75954edba0
	private Boolean _IsForceAvail(String forceId) { }
	// RVA: 0x2ed57dc VA: 0x75954ed7dc
	private Boolean _CanCharShowUp(HandBookV2GroupCharViewModel charViewModel) { }
	// RVA: 0x2ed6158 VA: 0x75954ee158
	public Void .ctor() { }
}
```