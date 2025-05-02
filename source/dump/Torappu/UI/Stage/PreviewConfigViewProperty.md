# PreviewConfigViewProperty

**Namespace:** `Torappu.UI.Stage`


## Methods

- `Void OnStageSelected(StageViewModel, IStageSelectHandler, Config)`

- `Void RefreshPluginRelatedData(StageViewModel, IStageSelectHandler)`

- `Void _SetDataPluginRelated(StageViewModel, IPreviewConfigViewModelPlugin, ref)`

- `Boolean _CheckCanHardBattle(StageViewModel, IStageSelectHandler)`

- `Boolean _CheckCanSixStarBattle(StageViewModel, IStageSelectHandler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class PreviewConfigViewProperty : DynamicBindProperty`2
{


	// RVA: 0x2f775bc VA: 0x759558f5bc
	public Void OnStageSelected(StageViewModel stageModel, IStageSelectHandler selectStageHandler, Config config) { }
	// RVA: 0x2f78088 VA: 0x7595590088
	public Void RefreshPluginRelatedData(StageViewModel stageModel, IStageSelectHandler selectStageHandler) { }
	// RVA: 0x2f77850 VA: 0x759558f850
	private Void _SetDataPluginRelated(StageViewModel stageModel, IPreviewConfigViewModelPlugin plugin, ref PreviewConfigViewModel viewModel) { }
	// RVA: 0x2f77d00 VA: 0x759558fd00
	private Boolean _CheckCanHardBattle(StageViewModel stageModel, IStageSelectHandler stageHandler) { }
	// RVA: 0x2f77e00 VA: 0x759558fe00
	private Boolean _CheckCanSixStarBattle(StageViewModel normalStageModel, IStageSelectHandler stageHandler) { }
	// RVA: 0x2f783b4 VA: 0x75955903b4
	public Void .ctor() { }
}
```