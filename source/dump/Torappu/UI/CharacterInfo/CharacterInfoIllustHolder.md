# CharacterInfoIllustHolder

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single MAX_DRAG_DIS`

- `Transform _container`

- `CharacterInfoIllustItem _item`

- `UnityEvent _onDetailShow`

- `UIIntEvent _onDataApply`

- `UnityEvent _onDetailHide`

- `GameObject _dragPart`

- `Boolean m_ableToDrag`

- `Boolean m_isDragging`

- `Int32 m_currentFocusIndex`

- `Int32 m_currentMiddleIndex`


## Properties

- `Boolean m_haveLeft`

- `Boolean m_haveRight`


## Methods

- `Boolean get_m_haveLeft()`

- `Boolean get_m_haveRight()`

- `Boolean _EnsurePrefab(Int32, out)`

- `Void Render(List`1, Int32)`

- `Void _RefreshPos(Single)`

- `Void _RefreshSingleViewModel(Int32, CharacterInfoIllustItem)`

- `Void OnDrag(Int32)`

- `Int32 _ClampPos(Int32)`

- `Void OnEndDrag(Int32)`

- `Void OnRelease(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoIllustHolder : DataBinder`1, IHotfixable
{
	private const Int32 MAX_ONSIDE_COUNT; // 0x0
	private const Int32 MAX_COUNT; // 0x0
	public Single MAX_DRAG_DIS; // 0x20
	private Transform _container; // 0x28
	private CharacterInfoIllustItem _item; // 0x30
	private UnityEvent _onDetailShow; // 0x38
	private UIIntEvent _onDataApply; // 0x40
	private UnityEvent _onDetailHide; // 0x48
	private GameObject _dragPart; // 0x50
	private ListDict`2 m_items; // 0x58
	private Boolean m_ableToDrag; // 0x60
	private Boolean m_isDragging; // 0x61
	private Int32 m_currentFocusIndex; // 0x64
	private List`1 m_viewModelList; // 0x68
	private Int32 m_currentMiddleIndex; // 0x70
	private static DelegateBridge __Hotfix0_get_m_haveLeft; // 0x0
	private static DelegateBridge __Hotfix0_get_m_haveRight; // 0x8
	private static DelegateBridge __Hotfix0__EnsurePrefab; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__RefreshPos; // 0x28
	private static DelegateBridge __Hotfix0__RefreshSingleViewModel; // 0x30
	private static DelegateBridge __Hotfix0_OnDrag; // 0x38
	private static DelegateBridge __Hotfix0__ClampPos; // 0x40
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x48
	private static DelegateBridge __Hotfix0_OnRelease; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Boolean m_haveLeft { get; }
	private Boolean m_haveRight { get; }

	// RVA: 0x2d71758 VA: 0x7595389758
	private Boolean get_m_haveLeft() { }
	// RVA: 0x2d717c8 VA: 0x75953897c8
	private Boolean get_m_haveRight() { }
	// RVA: 0x2d7185c VA: 0x759538985c
	private Boolean _EnsurePrefab(Int32 index, out CharacterInfoIllustItem item) { }
	// RVA: 0x2d719e4 VA: 0x75953899e4
	public override Void OnValueChanged(CharInfoGroupProperty property) { }
	// RVA: 0x2d71a94 VA: 0x7595389a94
	public Void Render(List`1 viewModelList, Int32 indexId) { }
	// RVA: 0x2d71cbc VA: 0x7595389cbc
	private Void _RefreshPos(Single pos) { }
	// RVA: 0x2d71b88 VA: 0x7595389b88
	private Void _RefreshSingleViewModel(Int32 viewI, CharacterInfoIllustItem item) { }
	// RVA: 0x2d71fa8 VA: 0x7595389fa8
	public Void OnDrag(Int32 pos) { }
	// RVA: 0x2d720a4 VA: 0x759538a0a4
	private Int32 _ClampPos(Int32 pos) { }
	// RVA: 0x2d721a0 VA: 0x759538a1a0
	public Void OnEndDrag(Int32 pos) { }
	// RVA: 0x2d722a0 VA: 0x759538a2a0
	public Void OnRelease(Int32 pos) { }
	// RVA: 0x2d7233c VA: 0x759538a33c
	public Void .ctor() { }
}
```