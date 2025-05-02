# UIRoguelikeFinishMissionDialog

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _textProgress`

- `Single _alphaComplted`

- `Slider _sliderProgress`

- `Text _textTaskName`

- `Text _textTaskDesc`

- `UIAtlasImage _imgRarity`

- `UIAtlasObject _atlas`

- `RoguelikeTaskCompleteModel m_taskModel`

- `Options m_options`


## Methods

- `Void _Render(RoguelikeTaskCompleteModel)`

- `Void OnFinishMission()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class UIRoguelikeFinishMissionDialog : UICustomDialog`1
{
	private Text _textProgress; // 0x48
	private Single _alphaComplted; // 0x50
	private Slider _sliderProgress; // 0x58
	private Text _textTaskName; // 0x60
	private Text _textTaskDesc; // 0x68
	private UIAtlasImage _imgRarity; // 0x70
	private UIAtlasObject _atlas; // 0x78
	private RoguelikeTaskCompleteModel m_taskModel; // 0x80
	private Options m_options; // 0x88
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0_OnFinishMission; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29e7f58 VA: 0x7594ffff58
	protected override Void OnRender(Options options) { }
	// RVA: 0x29e8030 VA: 0x7595000030
	private Void _Render(RoguelikeTaskCompleteModel taskModel) { }
	// RVA: 0x29e8350 VA: 0x7595000350
	public Void OnFinishMission() { }
	// RVA: 0x29e83e4 VA: 0x75950003e4
	public Void .ctor() { }
}
```