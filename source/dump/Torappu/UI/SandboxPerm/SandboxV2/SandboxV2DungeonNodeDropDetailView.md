# SandboxV2DungeonNodeDropDetailView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _enemyRushDropPanel`

- `GameObject _mainDropPanel`

- `GameObject _generalDropPanel`

- `SimpleLayoutContent _enemyRushDropContent`

- `SimpleLayoutContent _mainDropContent`

- `SimpleLayoutContent _generalDropContent`

- `Single _itemScale`

- `Boolean m_hasInited`

- `Adapter m_enemyRushDropAdapter`

- `Adapter m_mainDropAdapter`

- `Adapter m_generalDropAdapter`

- `Action <backEvent>k__BackingField`


## Properties

- `Action backEvent`


## Methods

- `Action get_backEvent()`

- `Void set_backEvent(Action)`

- `Void OnBackEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeDropDetailView : DataBinder`1
{
	private GameObject _enemyRushDropPanel; // 0x20
	private GameObject _mainDropPanel; // 0x28
	private GameObject _generalDropPanel; // 0x30
	private GameObject[] _normalDropInvalidPanels; // 0x38
	private SimpleLayoutContent _enemyRushDropContent; // 0x40
	private SimpleLayoutContent _mainDropContent; // 0x48
	private SimpleLayoutContent _generalDropContent; // 0x50
	private Single _itemScale; // 0x58
	private Boolean m_hasInited; // 0x5c
	private Adapter m_enemyRushDropAdapter; // 0x60
	private Adapter m_mainDropAdapter; // 0x68
	private Adapter m_generalDropAdapter; // 0x70
	private Action <backEvent>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_backEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_backEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action backEvent { get; set; }

	// RVA: 0x256a194 VA: 0x7594b82194
	private Action get_backEvent() { }
	// RVA: 0x256a1fc VA: 0x7594b821fc
	public Void set_backEvent(Action value) { }
	// RVA: 0x256a280 VA: 0x7594b82280
	public Void OnBackEvent() { }
	// RVA: 0x256a31c VA: 0x7594b8231c
	public override Void OnValueChanged(SandboxV2DungeonNodeDropDetailProperty property) { }
	// RVA: 0x256a528 VA: 0x7594b82528
	private Void _InitIfNot() { }
	// RVA: 0x256a774 VA: 0x7594b82774
	public Void .ctor() { }
}
```