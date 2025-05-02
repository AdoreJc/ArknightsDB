# RoguelikeModuleDialogController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `StateEngine _stateEngine`

- `IRoguelikeModuleDialogHandler m_dialogHandler`


## Properties

- `IRoguelikeModuleDialogHandler dialogHandler`


## Methods

- `IRoguelikeModuleDialogHandler get_dialogHandler()`

- `Void OpenModuleDialog(String, TInput, MenuConfig, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeModuleDialogController : PageSingleComponent
{
	private StateEngine _stateEngine; // 0x20
	private IRoguelikeModuleDialogHandler m_dialogHandler; // 0x28
	private static DelegateBridge __Hotfix0_get_dialogHandler; // 0x0
	private static DelegateBridge __Hotfix0_OpenModuleDialog; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public IRoguelikeModuleDialogHandler dialogHandler { get; }

	// RVA: 0x2a7f980 VA: 0x7595097980
	public IRoguelikeModuleDialogHandler get_dialogHandler() { }
	// RVA: 0x VA: 0x0
	public Void OpenModuleDialog(String resPath, TInput options, MenuConfig menuConfig, Single showTweenDuration) { }
	// RVA: 0x2a7f9e8 VA: 0x75950979e8
	public Void .ctor() { }
}
```