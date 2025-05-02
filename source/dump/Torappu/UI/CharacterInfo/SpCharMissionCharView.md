# SpCharMissionCharView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _textName`

- `UIAtlasImage _imagePortrait`

- `Button _buttonJumpTo`

- `Text _textCurrent`

- `Boolean m_inited`

- `SpCharMissionCharViewModel m_cacheModel`


## Methods

- `Void set_onJumpToClicked(Action`1)`

- `Void InitIfNot(CharacterInfoSpCharMissionView)`

- `Void Render(SpCharMissionCharViewModel)`

- `Void EventOnJumpToClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class SpCharMissionCharView : MonoBehaviour, IHotfixable
{
	private List`1 _missionObjViews; // 0x18
	private Text _textName; // 0x20
	private UIAtlasImage _imagePortrait; // 0x28
	private Button _buttonJumpTo; // 0x30
	private Text _textCurrent; // 0x38
	private Boolean m_inited; // 0x40
	private SpCharMissionCharViewModel m_cacheModel; // 0x48
	private Action`1 <onJumpToClicked>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onJumpToClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onJumpToClicked; // 0x8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnJumpToClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Action`1 onJumpToClicked { get; set; }

	// RVA: 0x2d8bc50 VA: 0x75953a3c50
	public Action`1 get_onJumpToClicked() { }
	// RVA: 0x2d8bcb8 VA: 0x75953a3cb8
	public Void set_onJumpToClicked(Action`1 value) { }
	// RVA: 0x2d8b894 VA: 0x75953a3894
	public Void InitIfNot(CharacterInfoSpCharMissionView context) { }
	// RVA: 0x2d8b9c4 VA: 0x75953a39c4
	public Void Render(SpCharMissionCharViewModel viewModel) { }
	// RVA: 0x2d8c260 VA: 0x75953a4260
	public Void EventOnJumpToClicked() { }
	// RVA: 0x2d8c300 VA: 0x75953a4300
	public Void .ctor() { }
}
```