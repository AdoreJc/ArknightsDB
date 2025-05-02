# RoguelikeMenuTaskWindow

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textTaskTitle`

- `Text _textTaskDesc`

- `Text _textTaskProgress`

- `Image _progressBar`

- `UIAtlasImage _taskRarityIcon`

- `UIAtlasObject _taskRarityIconAtlas`

- `GameObject _panelIncomplete`

- `GameObject _panelComplete`

- `CanvasGroup _canvasNormal`

- `CanvasGroup _canvasConfirm`

- `String m_cachedTaskId`

- `FadeSwitchTween m_normalShowTween`

- `FadeSwitchTween m_confirmShowTween`

- `Boolean m_init`


## Properties

- `Boolean canClick`


## Methods

- `Boolean get_canClick()`

- `Void _InitIfNot()`

- `Void _SetButtonState(Boolean, Boolean)`

- `Void OnBtnNormalClicked()`

- `Void OnBtnConfirmClicked()`

- `Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuTaskWindow : RoguelikeMenuWindow`1
{
	private const String PROGRESS_FORMAT; // 0x0
	private Text _textTaskTitle; // 0x28
	private Text _textTaskDesc; // 0x30
	private Text _textTaskProgress; // 0x38
	private Image _progressBar; // 0x40
	private UIAtlasImage _taskRarityIcon; // 0x48
	private UIAtlasObject _taskRarityIconAtlas; // 0x50
	private String[] _taskRarityIconNames; // 0x58
	private GameObject _panelIncomplete; // 0x60
	private GameObject _panelComplete; // 0x68
	private CanvasGroup _canvasNormal; // 0x70
	private CanvasGroup _canvasConfirm; // 0x78
	private String m_cachedTaskId; // 0x80
	private FadeSwitchTween m_normalShowTween; // 0x88
	private FadeSwitchTween m_confirmShowTween; // 0x90
	private Boolean m_init; // 0x98
	private static DelegateBridge __Hotfix0_get_canClick; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_get_selectType; // 0x10
	private static DelegateBridge __Hotfix0_RenderSelection; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__SetButtonState; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnNormalClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnConfirmClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean canClick { get; }
	public override RoguelikeMenuType selectType { get; }

	// RVA: 0x2a75804 VA: 0x759508d804
	private Boolean get_canClick() { }
	// RVA: 0x2a758a0 VA: 0x759508d8a0
	private Void _InitIfNot() { }
	// RVA: 0x2a759d0 VA: 0x759508d9d0
	public override RoguelikeMenuType get_selectType() { }
	// RVA: 0x2a75a38 VA: 0x759508da38
	public override Void RenderSelection(RoguelikeMenuType type, Boolean fastMode) { }
	// RVA: 0x2a75bd8 VA: 0x759508dbd8
	public override Void Render(RoguelikeMenuTaskViewModel viewModel) { }
	// RVA: 0x2a75b04 VA: 0x759508db04
	private Void _SetButtonState(Boolean showConfirm, Boolean fastMode) { }
	// RVA: 0x2a75eac VA: 0x759508deac
	public Void OnBtnNormalClicked() { }
	// RVA: 0x2a75f34 VA: 0x759508df34
	public Void OnBtnConfirmClicked() { }
	// RVA: 0x2a76018 VA: 0x759508e018
	public Void .ctor() { }
	// RVA: 0x2a760a8 VA: 0x759508e0a8
	private Void <>xLuaBaseProxy_RenderSelection(RoguelikeMenuType P0, Boolean P1) { }
}
```