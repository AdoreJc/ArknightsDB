# HiddenStagePlugin

**Namespace:** `Torappu.UI.HiddenStage`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelUnlock`

- `GameObject _iconProgress`

- `GameObject _iconComplete`

- `GameObject _panelPlugin`

- `UICommonTrackPoint _hiddenStageTrackPoint`

- `String _anchorStageId`

- `TrackPointViewProperty m_trackProperty`


## Methods

- `Boolean _RenderLockedInfoOnInit(String)`

- `Void OnPluginClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStagePlugin : StageButtonHolderPlugin
{
	private GameObject _panelLocked; // 0x28
	private GameObject _panelUnlock; // 0x30
	private GameObject _iconProgress; // 0x38
	private GameObject _iconComplete; // 0x40
	private GameObject[] _lines; // 0x48
	private GameObject _panelPlugin; // 0x50
	private UICommonTrackPoint _hiddenStageTrackPoint; // 0x58
	private String _anchorStageId; // 0x60
	private TrackPointViewProperty m_trackProperty; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x8
	private static DelegateBridge __Hotfix0__RenderLockedInfoOnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnPluginClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x285ece8 VA: 0x7594e76ce8
	protected override Void OnInit() { }
	// RVA: 0x285ef0c VA: 0x7594e76f0c
	protected override Void OnRenderStage(StageViewModel stageViewModel) { }
	// RVA: 0x285edb8 VA: 0x7594e76db8
	private Boolean _RenderLockedInfoOnInit(String stageId) { }
	// RVA: 0x285f1a0 VA: 0x7594e771a0
	public Void OnPluginClick() { }
	// RVA: 0x285f2dc VA: 0x7594e772dc
	public Void .ctor() { }
}
```