# StagePreviewHardView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StagePreviewRankView _rankView`


## Methods

- `Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler, StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewHardView : StagePreviewInfoBasicPanel
{
	protected StagePreviewRankView _rankView; // 0x148
	private static DelegateBridge __Hotfix0_OnZoneViewChanged; // 0x0
	private static DelegateBridge __Hotfix0_SelectStageViewModel; // 0x8
	private static DelegateBridge __Hotfix0_CheckToShow; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f99e88 VA: 0x75955b1e88
	protected override Boolean OnZoneViewChanged(IStageSelectHandler zoneModel, StageViewModel stageModel) { }
	// RVA: 0x2f9a044 VA: 0x75955b2044
	protected override Boolean SelectStageViewModel(IStageSelectHandler zoneModel, out StageViewModel stageModel) { }
	// RVA: 0x2f9a1dc VA: 0x75955b21dc
	protected override Boolean CheckToShow(IStageSelectHandler zoneModel) { }
	// RVA: 0x2f9a2d0 VA: 0x75955b22d0
	public Void .ctor() { }
	// RVA: 0x2f9a340 VA: 0x75955b2340
	private Boolean <>xLuaBaseProxy_OnZoneViewChanged(IStageSelectHandler P0, StageViewModel P1) { }
}
```