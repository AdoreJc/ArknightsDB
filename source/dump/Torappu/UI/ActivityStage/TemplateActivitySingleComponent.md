# TemplateActivitySingleComponent

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `TemplateActivityController templateController`


## Methods

- `Void RefreshBinder()`

- `Void BindController(TemplateActivityController)`

- `Void <>xLuaBaseProxy_OnControllerBinded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivitySingleComponent : ActivityStageSingleComponent
{
	private List`1 _pluginList; // 0x20
	protected TemplateActivityController templateController; // 0x28
	private static DelegateBridge __Hotfix0_OnControllerBinded; // 0x0
	private static DelegateBridge __Hotfix0_RefreshBinder; // 0x8
	private static DelegateBridge __Hotfix0_BindController; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30a4408 VA: 0x75956bc408
	protected override Void OnControllerBinded() { }
	// RVA: 0x30a03a4 VA: 0x75956b83a4
	public Void RefreshBinder() { }
	// RVA: 0x30a451c VA: 0x75956bc51c
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x30a3edc VA: 0x75956bbedc
	public Void .ctor() { }
	// RVA: 0x30a464c VA: 0x75956bc64c
	private Void <>xLuaBaseProxy_OnControllerBinded() { }
}
```