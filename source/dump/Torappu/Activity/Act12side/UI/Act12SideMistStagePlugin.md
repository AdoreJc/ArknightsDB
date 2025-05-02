# Act12SideMistStagePlugin

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `GameObject _panelLocked`

- `Text _textTimeCond`

- `Text _textStageCond`

- `GameObject _slashTimeCond`

- `GameObject _slashStageCond`

- `GameObject _panelUnlocked`

- `Text _textCurCount`

- `Text _textTargetCount`

- `Int32 _mistTargetCount`

- `GameObject _panelPlugin`

- `String _anchorStageId`


## Methods

- `Boolean _CheckIfPluginActive(StageViewModel)`

- `Boolean _RenderLockedInfoOnInit(String)`

- `Void _RenderUnlocked(StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12SideMistStagePlugin : StageButtonHolderPlugin
{
	private GameObject _panelLocked; // 0x28
	private Text _textTimeCond; // 0x30
	private Text _textStageCond; // 0x38
	private GameObject _slashTimeCond; // 0x40
	private GameObject _slashStageCond; // 0x48
	private GameObject _panelUnlocked; // 0x50
	private Text _textCurCount; // 0x58
	private Text _textTargetCount; // 0x60
	private Int32 _mistTargetCount; // 0x68
	private GameObject _panelPlugin; // 0x70
	private String _anchorStageId; // 0x78
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfPluginActive; // 0x10
	private static DelegateBridge __Hotfix0__RenderLockedInfoOnInit; // 0x18
	private static DelegateBridge __Hotfix0__RenderUnlocked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x345b7e8 VA: 0x7595a737e8
	protected override Void OnInit() { }
	// RVA: 0x345baf0 VA: 0x7595a73af0
	protected override Void OnRenderStage(StageViewModel nullableModel) { }
	// RVA: 0x345bbe8 VA: 0x7595a73be8
	private Boolean _CheckIfPluginActive(StageViewModel model) { }
	// RVA: 0x345b884 VA: 0x7595a73884
	private Boolean _RenderLockedInfoOnInit(String stageId) { }
	// RVA: 0x345bcac VA: 0x7595a73cac
	private Void _RenderUnlocked(StageViewModel model) { }
	// RVA: 0x345be4c VA: 0x7595a73e4c
	public Void .ctor() { }
}
```