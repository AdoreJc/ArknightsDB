# BuildingLaborDetailView

**Namespace:** `Torappu.Building.UI`


## Fields

- `FillProgressBar _progress`

- `Text _textTimeRemain`

- `Text _textSpeedBuff`

- `GameObject _lockBuyLabor`

- `GameObject _arrowIcon`

- `UIAnimationLocation _animShow`

- `RectTransform _panelBlankContainer`

- `RectTransform _blankPrefab`

- `Color _colorSpeedBuff`

- `BuildingLaborViewModel m_laborModel`

- `AnimationSwitchTween m_switchTween`

- `GameObject m_blankInst`

- `Boolean m_isInited`

- `Canvas m_rootCanvas`


## Properties

- `Canvas rootCanvas`

- `AnimationSwitchTween switchTween`


## Methods

- `Canvas get_rootCanvas()`

- `AnimationSwitchTween get_switchTween()`

- `Void RenderContent()`

- `Void Show()`

- `Void _InitIfNot()`

- `Void _AddBlankIfNeeded()`

- `Void _RemoveBlank()`

- `Void _RenderLabor()`

- `Void Update()`

- `Void EventOnBuyLaborClicked()`

- `Void _OnBlankClicked()`

- `Void _OnLaborTimeTick(BuildingLaborViewModel)`

- `Void _OnLaborChange(BuildingLaborViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingLaborDetailView : MonoBehaviour
{
	private const String EMPTY_TIME; // 0x0
	private FillProgressBar _progress; // 0x18
	private Text _textTimeRemain; // 0x20
	private Text _textSpeedBuff; // 0x28
	private GameObject _lockBuyLabor; // 0x30
	private GameObject _arrowIcon; // 0x38
	private UIAnimationLocation _animShow; // 0x40
	private RectTransform _panelBlankContainer; // 0x50
	private RectTransform _blankPrefab; // 0x58
	private Color _colorSpeedBuff; // 0x60
	private BuildingLaborViewModel m_laborModel; // 0x70
	private AnimationSwitchTween m_switchTween; // 0x78
	private GameObject m_blankInst; // 0x80
	private Boolean m_isInited; // 0x88
	private Canvas m_rootCanvas; // 0x90

	protected Canvas rootCanvas { get; }
	protected AnimationSwitchTween switchTween { get; }

	// RVA: 0x3d3d324 VA: 0x7596355324
	protected Canvas get_rootCanvas() { }
	// RVA: 0x3d3d418 VA: 0x7596355418
	protected AnimationSwitchTween get_switchTween() { }
	// RVA: 0x3d3d4c4 VA: 0x75963554c4
	public Void RenderContent() { }
	// RVA: 0x3d3da78 VA: 0x7596355a78
	public Void Show() { }
	// RVA: 0x3d3d744 VA: 0x7596355744
	private Void _InitIfNot() { }
	// RVA: 0x3d3daa0 VA: 0x7596355aa0
	private Void _AddBlankIfNeeded() { }
	// RVA: 0x3d3de94 VA: 0x7596355e94
	private Void _RemoveBlank() { }
	// RVA: 0x3d3d85c VA: 0x759635585c
	private Void _RenderLabor() { }
	// RVA: 0x3d3df10 VA: 0x7596355f10
	private Void Update() { }
	// RVA: 0x3d3df2c VA: 0x7596355f2c
	public Void EventOnBuyLaborClicked() { }
	// RVA: 0x3d3e150 VA: 0x7596356150
	private Void _OnBlankClicked() { }
	// RVA: 0x3d3e178 VA: 0x7596356178
	private Void _OnLaborTimeTick(BuildingLaborViewModel laborModel) { }
	// RVA: 0x3d3e17c VA: 0x759635617c
	private Void _OnLaborChange(BuildingLaborViewModel laborModel) { }
	// RVA: 0x3d3e180 VA: 0x7596356180
	public Void .ctor() { }
}
```