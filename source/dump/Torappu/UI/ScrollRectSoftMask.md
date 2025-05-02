# ScrollRectSoftMask

**Namespace:** `Torappu.UI`


## Fields

- `Sprite _bothSprite`

- `Sprite _downSprite`

- `Sprite _upSprite`

- `RectTransform _content`

- `ScrollRect _scrollRect`

- `LoopScrollRect _loopScrollRect`

- `SoftMask _softMask`

- `Image _backMask`

- `Boolean _initOnEnable`

- `Boolean m_contentFlag`

- `RectTransform m_viewRect`

- `Vector2 m_cachedContentSize`

- `Vector2 m_cachedBoundSize`

- `Int32 m_cachedDirFlag`


## Properties

- `Vector2 normalizedPosition`

- `Boolean isHorizontal`

- `Boolean isVertical`

- `RectTransform viewRect`


## Methods

- `Vector2 get_normalizedPosition()`

- `Boolean get_isHorizontal()`

- `Boolean get_isVertical()`

- `RectTransform get_viewRect()`

- `Void Initialized()`

- `Void OnEnable()`

- `Void Update()`

- `Void Refresh()`

- `Void OnDrag(Vector2)`

- `Void _TryUpdateContentFlag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ScrollRectSoftMask : MonoBehaviour, IHotfixable
{
	private Sprite _bothSprite; // 0x18
	private Sprite _downSprite; // 0x20
	private Sprite _upSprite; // 0x28
	private RectTransform _content; // 0x30
	private ScrollRect _scrollRect; // 0x38
	private LoopScrollRect _loopScrollRect; // 0x40
	private SoftMask _softMask; // 0x48
	private Image _backMask; // 0x50
	private Boolean _initOnEnable; // 0x58
	private Boolean m_contentFlag; // 0x59
	private RectTransform m_viewRect; // 0x60
	private Vector2 m_cachedContentSize; // 0x68
	private Vector2 m_cachedBoundSize; // 0x70
	private Int32 m_cachedDirFlag; // 0x78
	private const Single EPS_DELTA; // 0x0
	private static DelegateBridge __Hotfix0_get_normalizedPosition; // 0x0
	private static DelegateBridge __Hotfix0_get_isHorizontal; // 0x8
	private static DelegateBridge __Hotfix0_get_isVertical; // 0x10
	private static DelegateBridge __Hotfix0_get_viewRect; // 0x18
	private static DelegateBridge __Hotfix0_Initialized; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0_Refresh; // 0x38
	private static DelegateBridge __Hotfix0_OnDrag; // 0x40
	private static DelegateBridge __Hotfix0__TryUpdateContentFlag; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Vector2 normalizedPosition { get; }
	public Boolean isHorizontal { get; }
	public Boolean isVertical { get; }
	protected RectTransform viewRect { get; }

	// RVA: 0x2239ae4 VA: 0x7594851ae4
	public Vector2 get_normalizedPosition() { }
	// RVA: 0x2239bac VA: 0x7594851bac
	public Boolean get_isHorizontal() { }
	// RVA: 0x2239c7c VA: 0x7594851c7c
	public Boolean get_isVertical() { }
	// RVA: 0x2239d4c VA: 0x7594851d4c
	protected RectTransform get_viewRect() { }
	// RVA: 0x2239e9c VA: 0x7594851e9c
	public Void Initialized() { }
	// RVA: 0x2239fa4 VA: 0x7594851fa4
	private Void OnEnable() { }
	// RVA: 0x223a020 VA: 0x7594852020
	private Void Update() { }
	// RVA: 0x223a280 VA: 0x7594852280
	public Void Refresh() { }
	// RVA: 0x223a2f0 VA: 0x75948522f0
	public Void OnDrag(Vector2 value) { }
	// RVA: 0x223a090 VA: 0x7594852090
	private Void _TryUpdateContentFlag() { }
	// RVA: 0x223a488 VA: 0x7594852488
	public Void .ctor() { }
}
```