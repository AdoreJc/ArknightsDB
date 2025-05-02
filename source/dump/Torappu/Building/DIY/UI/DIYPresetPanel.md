# DIYPresetPanel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYFurnitureScrollAdapter _adapter`

- `Sprite _emptyPresetIcon`

- `Button _loadButton`

- `Button _saveButton`

- `Sprite _presetIconInvalid`

- `Sprite _presetIconLoading`

- `Text _presetTitle`

- `IDIYPreset m_currentDIYPreset`

- `Int32 m_currentIndex`

- `IDIYPresetManager m_presetManager`

- `Action m_presetSaveCallback`

- `Tween m_currentTween`

- `Boolean m_shown`


## Properties

- `Boolean shown`


## Methods

- `Boolean get_shown()`

- `Action _GetTextureFetchFailedCallback(Int32, PresetViewData)`

- `Void Update()`

- `Void Setup(Params, Action`2, Action`2, Action)`

- `Void Render(Params)`

- `Void _SelectPreset(Int32)`

- `Boolean _OnPresetSelected(DIYItemViewData)`

- `Boolean _OnRenameButtonPressed(DIYItemViewData)`

- `Void _SetPresetTitleText()`

- `Int32 GetCurrentIndex()`

- `IDIYPreset GetCurrentPreset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYPresetPanel : MonoBehaviour, IHotfixable
{
	private DIYFurnitureScrollAdapter _adapter; // 0x18
	private Sprite _emptyPresetIcon; // 0x20
	private Button _loadButton; // 0x28
	private Button _saveButton; // 0x30
	private Sprite _presetIconInvalid; // 0x38
	private Sprite _presetIconLoading; // 0x40
	private Text _presetTitle; // 0x48
	private IDIYPreset m_currentDIYPreset; // 0x50
	private Int32 m_currentIndex; // 0x58
	private IDIYPresetManager m_presetManager; // 0x60
	private Action`2 m_presetRenameCallback; // 0x68
	private Action`2 m_presetLoadCallback; // 0x70
	private Action m_presetSaveCallback; // 0x78
	private Tween m_currentTween; // 0x80
	private Boolean m_shown; // 0x88
	private List`1 m_coroutines; // 0x90
	private static DelegateBridge __Hotfix0_get_shown; // 0x0
	private static DelegateBridge __Hotfix0__GetTextureFetchCallback; // 0x8
	private static DelegateBridge __Hotfix0__GetTextureFetchFailedCallback; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_Setup; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__SelectPreset; // 0x30
	private static DelegateBridge __Hotfix0__OnPresetSelected; // 0x38
	private static DelegateBridge __Hotfix0__OnRenameButtonPressed; // 0x40
	private static DelegateBridge __Hotfix0__SetPresetTitleText; // 0x48
	private static DelegateBridge __Hotfix0_GetCurrentIndex; // 0x50
	private static DelegateBridge __Hotfix0_GetCurrentPreset; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean shown { get; }

	// RVA: 0x3823510 VA: 0x7595e3b510
	public Boolean get_shown() { }
	// RVA: 0x3823578 VA: 0x7595e3b578
	private Action`1 _GetTextureFetchCallback(Int32 index, PresetViewData presetData, DIYFurnitureScrollAdapter adapter) { }
	// RVA: 0x38236b8 VA: 0x7595e3b6b8
	private Action _GetTextureFetchFailedCallback(Int32 index, PresetViewData presetData) { }
	// RVA: 0x38237e4 VA: 0x7595e3b7e4
	private Void Update() { }
	// RVA: 0x3823934 VA: 0x7595e3b934
	public Void Setup(Params param, Action`2 renameCallback, Action`2 loadCallback, Action saveCallback) { }
	// RVA: 0x3823a28 VA: 0x7595e3ba28
	public Void Render(Params param) { }
	// RVA: 0x38247c8 VA: 0x7595e3c7c8
	private Void _SelectPreset(Int32 index) { }
	// RVA: 0x3824ab0 VA: 0x7595e3cab0
	private Boolean _OnPresetSelected(DIYItemViewData data) { }
	// RVA: 0x3824b7c VA: 0x7595e3cb7c
	private Boolean _OnRenameButtonPressed(DIYItemViewData data) { }
	// RVA: 0x382442c VA: 0x7595e3c42c
	private Void _SetPresetTitleText() { }
	// RVA: 0x3824c74 VA: 0x7595e3cc74
	public Int32 GetCurrentIndex() { }
	// RVA: 0x3824d40 VA: 0x7595e3cd40
	public IDIYPreset GetCurrentPreset() { }
	// RVA: 0x3824da8 VA: 0x7595e3cda8
	public Void .ctor() { }
}
```