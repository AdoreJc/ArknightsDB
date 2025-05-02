# SandboxV2DungeonMapView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonLayerContainer _layerContainer`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`

- `SandboxV2DungeonViewConfig m_dungeonViewConfig`

- `SeqNumChecker m_dungeonConstructChecker`

- `SandboxV2DungeonViewModel m_cachedDungeonViewModel`

- `BackgroundViewPool m_backgroundViewPool`

- `SeqNumChecker m_backgroundViewPoolChecker`

- `NodeViewPool m_nodeViewPool`

- `SeqNumChecker m_nodeViewPoolChecker`

- `NodeShadowViewPool m_nodeShadowViewPool`

- `SeqNumChecker m_nodeShadowViewPoolChecker`

- `LineViewPool m_lineViewPool`

- `SeqNumChecker m_lineViewPoolChecker`

- `ZoneViewPool m_zoneViewPool`

- `SeqNumChecker m_zoneViewPoolChecker`

- `EnemyRushLineViewPool m_enemyRushLineViewPool`

- `SeqNumChecker m_enemyRushLineViewPoolChecker`

- `NodeFloatViewPool m_nodeFloatViewPool`

- `SeqNumChecker m_nodeFloatViewPoolChecker`


## Properties

- `SandboxV2DungeonLayerContainer layerContainer`


## Methods

- `SandboxV2DungeonLayerContainer get_layerContainer()`

- `Void _InitIfNot()`

- `Void _ConstructDungeonView(SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMapView : DataBinder`1
{
	private SandboxV2DungeonLayerContainer _layerContainer; // 0x20
	private Boolean m_inited; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private SandboxV2DungeonViewConfig m_dungeonViewConfig; // 0x40
	private SeqNumChecker m_dungeonConstructChecker; // 0x48
	private SandboxV2DungeonViewModel m_cachedDungeonViewModel; // 0x58
	private ListDict`2 m_cachedDungeonBackgroundConfig; // 0x60
	private Dictionary`2 m_cachedNodeViewModelGroup; // 0x68
	private Dictionary`2 m_cachedLineViewModelGroup; // 0x70
	private Dictionary`2 m_cachedZoneViewModelGroup; // 0x78
	private Dictionary`2 m_cachedEnemyRushLineViewModelGroup; // 0x80
	private List`1 m_cachedNodeViewModelList; // 0x88
	private BackgroundViewPool m_backgroundViewPool; // 0x90
	private SeqNumChecker m_backgroundViewPoolChecker; // 0x98
	private NodeViewPool m_nodeViewPool; // 0xa8
	private SeqNumChecker m_nodeViewPoolChecker; // 0xb0
	private NodeShadowViewPool m_nodeShadowViewPool; // 0xc0
	private SeqNumChecker m_nodeShadowViewPoolChecker; // 0xc8
	private LineViewPool m_lineViewPool; // 0xd8
	private SeqNumChecker m_lineViewPoolChecker; // 0xe0
	private ZoneViewPool m_zoneViewPool; // 0xf0
	private SeqNumChecker m_zoneViewPoolChecker; // 0xf8
	private EnemyRushLineViewPool m_enemyRushLineViewPool; // 0x108
	private SeqNumChecker m_enemyRushLineViewPoolChecker; // 0x110
	private NodeFloatViewPool m_nodeFloatViewPool; // 0x120
	private SeqNumChecker m_nodeFloatViewPoolChecker; // 0x128
	private static DelegateBridge __Hotfix0_get_layerContainer; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ConstructDungeonView; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public SandboxV2DungeonLayerContainer layerContainer { get; }

	// RVA: 0x2570ce4 VA: 0x7594b88ce4
	public SandboxV2DungeonLayerContainer get_layerContainer() { }
	// RVA: 0x2570d4c VA: 0x7594b88d4c
	private Void _InitIfNot() { }
	// RVA: 0x2571364 VA: 0x7594b89364
	private Void _ConstructDungeonView(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x2571514 VA: 0x7594b89514
	public override Void OnValueChanged(SandboxV2DungeonProperty property) { }
	// RVA: 0x2571860 VA: 0x7594b89860
	public Void .ctor() { }
}
```