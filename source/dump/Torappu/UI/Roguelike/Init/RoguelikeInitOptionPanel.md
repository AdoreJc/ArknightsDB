# RoguelikeInitOptionPanel

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `RectTransform _listRoot`

- `ScrollRect _scrollRect`

- `RectTransform _scrollViewport`

- `Single _rightHintThreshold`

- `GameObject _rightHintPanel`

- `GameObject _supportHint`


## Methods

- `RoguelikeInitOption _CreateOption()`

- `Void _SetOptionActive(Int32)`

- `Void _SetAllOptionActive(Func`2)`

- `Void _EventOptionSelectResponse(Int32)`

- `Void EventBackgroundPressed()`

- `Void Update()`

- `Void _Adjust()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitOptionPanel : RoguelikeInitStepPanel`1
{
	private RectTransform _listRoot; // 0x38
	private ScrollRect _scrollRect; // 0x40
	private RectTransform _scrollViewport; // 0x48
	private Single _rightHintThreshold; // 0x50
	private GameObject _rightHintPanel; // 0x58
	private GameObject _supportHint; // 0x60
	private ItemPool`1 m_options; // 0x68
	private static DelegateBridge __Hotfix0__CreateOption; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdateContext; // 0x8
	private static DelegateBridge __Hotfix0__SetOptionActive; // 0x10
	private static DelegateBridge __Hotfix0__SetAllOptionActive; // 0x18
	private static DelegateBridge __Hotfix0__EventOptionSelectResponse; // 0x20
	private static DelegateBridge __Hotfix0_EventBackgroundPressed; // 0x28
	private static DelegateBridge __Hotfix0_Update; // 0x30
	private static DelegateBridge __Hotfix0__Adjust; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2b87124 VA: 0x759519f124
	private RoguelikeInitOption _CreateOption() { }
	// RVA: 0x2b873e0 VA: 0x759519f3e0
	protected override Void OnUpdateContext(Boolean isNew) { }
	// RVA: 0x2b879a8 VA: 0x759519f9a8
	private Void _SetOptionActive(Int32 idx) { }
	// RVA: 0x2b87aac VA: 0x759519faac
	private Void _SetAllOptionActive(Func`2 pred) { }
	// RVA: 0x2b87c00 VA: 0x759519fc00
	private Void _EventOptionSelectResponse(Int32 idx) { }
	// RVA: 0x2b87cac VA: 0x759519fcac
	public Void EventBackgroundPressed() { }
	// RVA: 0x2b87dd4 VA: 0x759519fdd4
	private Void Update() { }
	// RVA: 0x2b87774 VA: 0x759519f774
	private Void _Adjust() { }
	// RVA: 0x2b87f08 VA: 0x759519ff08
	public Void .ctor() { }
}
```