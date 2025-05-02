# Act13SideHiddenAreaPlugin

**Namespace:** `Torappu.Activity.Act13Side.UI`


## Fields

- `Color _lockedTextColor`

- `Color _unlockedTextColor`

- `GameObject _panelLocked`

- `Text _preposedTimeInfo`

- `GameObject _preposedTimeMark`

- `GameObject _panelTimeText`

- `GameObject _panelUnlocked`

- `GameObject _panelPlugin`

- `String _anchorStageId`

- `String _hiddenAreaId`

- `ActivityHiddenAreaData m_hiddenAreaData`


## Methods

- `Boolean _RenderLockedInfoOnInit(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side.UI
public class Act13SideHiddenAreaPlugin : StageButtonHolderPlugin
{
	private Color _lockedTextColor; // 0x28
	private Color _unlockedTextColor; // 0x38
	private GameObject _panelLocked; // 0x48
	private Text[] _preposedStageText; // 0x50
	private GameObject[] _preposedStageMark; // 0x58
	private Text _preposedTimeInfo; // 0x60
	private GameObject _preposedTimeMark; // 0x68
	private GameObject _panelTimeText; // 0x70
	private GameObject _panelUnlocked; // 0x78
	private GameObject _panelPlugin; // 0x80
	private String _anchorStageId; // 0x88
	private String _hiddenAreaId; // 0x90
	private ActivityHiddenAreaData m_hiddenAreaData; // 0x98
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x8
	private static DelegateBridge __Hotfix0__RenderLockedInfoOnInit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3444780 VA: 0x7595a5c780
	protected override Void OnInit() { }
	// RVA: 0x3444d44 VA: 0x7595a5cd44
	protected override Void OnRenderStage(StageViewModel model) { }
	// RVA: 0x344481c VA: 0x7595a5c81c
	private Boolean _RenderLockedInfoOnInit(String stageId) { }
	// RVA: 0x3444de8 VA: 0x7595a5cde8
	public Void .ctor() { }
}
```