# StagePreviewInfoHardPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StagePreviewRankView _rankView`


## Methods

- `Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler, StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewInfoHardPanel : StagePreviewInfoBasicPanel
{
	protected StagePreviewRankView _rankView; // 0x148
	private static DelegateBridge __Hotfix0_OnZoneViewChanged; // 0x0
	private static DelegateBridge __Hotfix0_SelectStageViewModel; // 0x8
	private static DelegateBridge __Hotfix0_CheckToShow; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fa8e00 VA: 0x75955c0e00
	protected override Boolean OnZoneViewChanged(IStageSelectHandler zoneModel, StageViewModel stageModel) { }
	// RVA: 0x2fa91d4 VA: 0x75955c11d4
	protected override Boolean SelectStageViewModel(IStageSelectHandler zoneModel, out StageViewModel stageModel) { }
	// RVA: 0x2fa936c VA: 0x75955c136c
	protected override Boolean CheckToShow(IStageSelectHandler zoneModel) { }
	// RVA: 0x2fa9460 VA: 0x75955c1460
	public Void .ctor() { }
	// RVA: 0x2fa9584 VA: 0x75955c1584
	private Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler P0, StageViewModel P1) { }
}
```