# Act1VAutoChessHUDView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessHUDTopView _topView`

- `Act1VAutoChessHUDMidView _midView`

- `Act1VAutoChessHUDBlurBackPanel _blurPanel`

- `GameObject _tutorialOnly_focusPanel`

- `GameObject _tutorialOnly_optionButton`

- `GameObject _tutorialOnly_confirmButton`

- `GameObject _tutorialOnly_selfCamp`

- `GameObject _tutorialOnly_enemyCamp`


## Methods

- `Void TutorialOnly_TryRegisterCampTutorialGO()`

- `Void TutorialOnly_TryRegisterCampSelfInfoTutorialGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDView : DataBinder`1
{
	private Act1VAutoChessHUDTopView _topView; // 0x20
	private Act1VAutoChessHUDMidView _midView; // 0x28
	private Act1VAutoChessHUDBlurBackPanel _blurPanel; // 0x30
	private GameObject _tutorialOnly_focusPanel; // 0x38
	private GameObject _tutorialOnly_optionButton; // 0x40
	private GameObject _tutorialOnly_confirmButton; // 0x48
	private GameObject _tutorialOnly_selfCamp; // 0x50
	private GameObject _tutorialOnly_enemyCamp; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnly_TryRegisterCampTutorialGO; // 0x8
	private static DelegateBridge __Hotfix0_TutorialOnly_TryRegisterCampSelfInfoTutorialGO; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x337f448 VA: 0x7595997448
	public override Void OnValueChanged(Act1VAutoChessHUDProperty property) { }
	// RVA: 0x3377bbc VA: 0x759598fbbc
	public Void TutorialOnly_TryRegisterCampTutorialGO() { }
	// RVA: 0x3377d4c VA: 0x759598fd4c
	public Void TutorialOnly_TryRegisterCampSelfInfoTutorialGO() { }
	// RVA: 0x337f544 VA: 0x7595997544
	public Void .ctor() { }
}
```