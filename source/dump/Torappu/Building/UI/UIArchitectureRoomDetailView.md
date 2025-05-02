# UIArchitectureRoomDetailView

**Namespace:** `Torappu.Building.UI`


## Fields

- `Text _nameText`

- `Text _descText`

- `GameObject _teardownButton`

- `GameObject _levelupButton`

- `RectTransform _infoRoot`

- `GameObject _infoProto`

- `CanvasGroup _canvasGroup`

- `Single _tweenDuration`

- `Single _tweenHorizontalTranslation`

- `Transform _mainPanel`

- `SimpleLayoutContent _levelPanel`

- `Color _levelEmptyColor`

- `Action m_onTearDown`

- `Action m_onLevelup`

- `Tweener m_transferTweener`

- `Vector3 m_fromPosition`

- `Vector3 m_toPosition`

- `Single m_transferVal`

- `Boolean m_shown`

- `Button m_levelupButton`

- `Button m_teardownButton`

- `UIBuildingLevelPanelAdapter m_buildingLevelPanelAdapter`


## Properties

- `Button levelupButton`

- `Button teardownButton`


## Methods

- `Button get_levelupButton()`

- `Button get_teardownButton()`

- `Void Awake()`

- `Void _TweenUpdateShow(Single)`

- `Void _TweenUpdateHide(Single)`

- `Void Setup(String, Int32, Int32, Color, List`1, String, Boolean, Boolean, Action, Action, Boolean)`

- `Void OnTeardownButtonPressed()`

- `Void OnLevelupButtonPressed()`

- `Void OnBGButtonPressed()`

- `Void Show()`

- `Void Hide()`

- `Single <Show>b__33_0()`

- `Void <Show>b__33_1()`

- `Single <Hide>b__34_0()`

- `Void <Hide>b__34_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIArchitectureRoomDetailView : MonoBehaviour
{
	private Text _nameText; // 0x18
	private Text _descText; // 0x20
	private GameObject _teardownButton; // 0x28
	private GameObject _levelupButton; // 0x30
	private RectTransform _infoRoot; // 0x38
	private GameObject _infoProto; // 0x40
	private CanvasGroup _canvasGroup; // 0x48
	private Single _tweenDuration; // 0x50
	private Single _tweenHorizontalTranslation; // 0x54
	private Transform _mainPanel; // 0x58
	private SimpleLayoutContent _levelPanel; // 0x60
	private Color _levelEmptyColor; // 0x68
	private Action m_onTearDown; // 0x78
	private Action m_onLevelup; // 0x80
	private Tweener m_transferTweener; // 0x88
	private Vector3 m_fromPosition; // 0x90
	private Vector3 m_toPosition; // 0x9c
	private Single m_transferVal; // 0xa8
	private Boolean m_shown; // 0xac
	private Button m_levelupButton; // 0xb0
	private Button m_teardownButton; // 0xb8
	private UIBuildingLevelPanelAdapter m_buildingLevelPanelAdapter; // 0xc0

	private Button levelupButton { get; }
	private Button teardownButton { get; }

	// RVA: 0x3d4a818 VA: 0x7596362818
	private Button get_levelupButton() { }
	// RVA: 0x3d4a8f0 VA: 0x75963628f0
	private Button get_teardownButton() { }
	// RVA: 0x3d4a9c8 VA: 0x75963629c8
	private Void Awake() { }
	// RVA: 0x3d4aacc VA: 0x7596362acc
	private Void _TweenUpdateShow(Single val) { }
	// RVA: 0x3d4abe0 VA: 0x7596362be0
	private Void _TweenUpdateHide(Single val) { }
	// RVA: 0x3d4abec VA: 0x7596362bec
	public Void Setup(String name, Int32 level, Int32 maxLevel, Color levelPanelColor, List`1 levelInfoItems, String desc, Boolean teardownInteractable, Boolean showButtonLevelup, Action onTeardown, Action onLevelup, Boolean levelupInteractable) { }
	// RVA: 0x3d4b1c0 VA: 0x75963631c0
	public Void OnTeardownButtonPressed() { }
	// RVA: 0x3d4b504 VA: 0x7596363504
	public Void OnLevelupButtonPressed() { }
	// RVA: 0x3d4b568 VA: 0x7596363568
	public Void OnBGButtonPressed() { }
	// RVA: 0x3d4b56c VA: 0x759636356c
	public Void Show() { }
	// RVA: 0x3d4b224 VA: 0x7596363224
	public Void Hide() { }
	// RVA: 0x3d4b870 VA: 0x7596363870
	public Void .ctor() { }
	// RVA: 0x3d4b934 VA: 0x7596363934
	private Single <Show>b__33_0() { }
	// RVA: 0x3d4b93c VA: 0x759636393c
	private Void <Show>b__33_1() { }
	// RVA: 0x3d4b958 VA: 0x7596363958
	private Single <Hide>b__34_0() { }
	// RVA: 0x3d4b960 VA: 0x7596363960
	private Void <Hide>b__34_1() { }
}
```