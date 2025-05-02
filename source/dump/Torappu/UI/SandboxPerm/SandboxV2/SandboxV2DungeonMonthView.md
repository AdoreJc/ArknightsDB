# SandboxV2DungeonMonthView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _rushName`

- `Text _updateTime`

- `GameObject _updateTimeNode`

- `Text _rushIdxLabel`

- `GameObject _completeTipNode`

- `Text _rushDesc`

- `EasyInstancePool _dotPool`

- `GameObject _pager`

- `Text _baseHpRatio`

- `Scrollbar _baseHpPrg`

- `Text _desc`

- `Text _mechanismInfo`

- `SimpleLayoutContent _rewardList`

- `GameObject _gotRewardNode`

- `Transform _weatherContainer`

- `SandboxV2NodePreviewWeatherView _weatherViewPrefab`

- `TwoStateToggle _startBtnValidToggle`

- `TwoStateToggle _startBtnHighlightToggle`

- `SandboxV2DungeonMonthModelProperty m_cachedProp`

- `SandboxV2NodePreviewWeatherView m_weatherView`

- `Adapter m_rewardAdapter`

- `Action <onOpenMap>k__BackingField`

- `Action <onOpenEenemy>k__BackingField`

- `Action <onStart>k__BackingField`


## Properties

- `Action onOpenMap`

- `Action onOpenEenemy`

- `Action onStart`


## Methods

- `Void set_onOpenMap(Action)`

- `Action get_onOpenMap()`

- `Void set_onOpenEenemy(Action)`

- `Action get_onOpenEenemy()`

- `Void set_onStart(Action)`

- `Action get_onStart()`

- `Void _Render(SandboxV2DungeonMonthModel)`

- `Void _RenderPortable(SandboxV2DungeonMonthModel)`

- `Void _RenderDot(SandboxV2DungeonMonthModel)`

- `Void _InitIfNot()`

- `Void EventShowTip()`

- `Void EventNext()`

- `Void EventPrev()`

- `Void EventOpenEnemy()`

- `Void EventOpenMap()`

- `Void EventStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMonthView : DataBinder`1, IHotfixable
{
	private Text _rushName; // 0x20
	private Text _updateTime; // 0x28
	private GameObject _updateTimeNode; // 0x30
	private Text _rushIdxLabel; // 0x38
	private GameObject _completeTipNode; // 0x40
	private Text _rushDesc; // 0x48
	private EasyInstancePool _dotPool; // 0x50
	private GameObject _pager; // 0x58
	private Text _baseHpRatio; // 0x60
	private Scrollbar _baseHpPrg; // 0x68
	private Text _desc; // 0x70
	private Text _mechanismInfo; // 0x78
	private SimpleLayoutContent _rewardList; // 0x80
	private GameObject _gotRewardNode; // 0x88
	private Transform _weatherContainer; // 0x90
	private SandboxV2NodePreviewWeatherView _weatherViewPrefab; // 0x98
	private TwoStateToggle _startBtnValidToggle; // 0xa0
	private TwoStateToggle _startBtnHighlightToggle; // 0xa8
	private SandboxV2DungeonMonthModelProperty m_cachedProp; // 0xb0
	private SandboxV2NodePreviewWeatherView m_weatherView; // 0xb8
	private Adapter m_rewardAdapter; // 0xc0
	private Action <onOpenMap>k__BackingField; // 0xc8
	private Action <onOpenEenemy>k__BackingField; // 0xd0
	private Action <onStart>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0_set_onOpenMap; // 0x0
	private static DelegateBridge __Hotfix0_get_onOpenMap; // 0x8
	private static DelegateBridge __Hotfix0_set_onOpenEenemy; // 0x10
	private static DelegateBridge __Hotfix0_get_onOpenEenemy; // 0x18
	private static DelegateBridge __Hotfix0_set_onStart; // 0x20
	private static DelegateBridge __Hotfix0_get_onStart; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__Render; // 0x38
	private static DelegateBridge __Hotfix0__RenderPortable; // 0x40
	private static DelegateBridge __Hotfix0__RenderDot; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0_EventShowTip; // 0x58
	private static DelegateBridge __Hotfix0_EventNext; // 0x60
	private static DelegateBridge __Hotfix0_EventPrev; // 0x68
	private static DelegateBridge __Hotfix0_EventOpenEnemy; // 0x70
	private static DelegateBridge __Hotfix0_EventOpenMap; // 0x78
	private static DelegateBridge __Hotfix0_EventStart; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	private Action onOpenMap { get; set; }
	private Action onOpenEenemy { get; set; }
	private Action onStart { get; set; }

	// RVA: 0x25315e4 VA: 0x7594b495e4
	public Void set_onOpenMap(Action value) { }
	// RVA: 0x2532390 VA: 0x7594b4a390
	private Action get_onOpenMap() { }
	// RVA: 0x2531560 VA: 0x7594b49560
	public Void set_onOpenEenemy(Action value) { }
	// RVA: 0x25323f8 VA: 0x7594b4a3f8
	private Action get_onOpenEenemy() { }
	// RVA: 0x2531668 VA: 0x7594b49668
	public Void set_onStart(Action value) { }
	// RVA: 0x2532460 VA: 0x7594b4a460
	private Action get_onStart() { }
	// RVA: 0x25324c8 VA: 0x7594b4a4c8
	public override Void OnValueChanged(SandboxV2DungeonMonthModelProperty property) { }
	// RVA: 0x25326ec VA: 0x7594b4a6ec
	private Void _Render(SandboxV2DungeonMonthModel model) { }
	// RVA: 0x2532bf4 VA: 0x7594b4abf4
	private Void _RenderPortable(SandboxV2DungeonMonthModel model) { }
	// RVA: 0x2532a5c VA: 0x7594b4aa5c
	private Void _RenderDot(SandboxV2DungeonMonthModel model) { }
	// RVA: 0x2532588 VA: 0x7594b4a588
	private Void _InitIfNot() { }
	// RVA: 0x2532f78 VA: 0x7594b4af78
	public Void EventShowTip() { }
	// RVA: 0x2532fdc VA: 0x7594b4afdc
	public Void EventNext() { }
	// RVA: 0x2533090 VA: 0x7594b4b090
	public Void EventPrev() { }
	// RVA: 0x2533144 VA: 0x7594b4b144
	public Void EventOpenEnemy() { }
	// RVA: 0x25331e0 VA: 0x7594b4b1e0
	public Void EventOpenMap() { }
	// RVA: 0x253327c VA: 0x7594b4b27c
	public Void EventStart() { }
	// RVA: 0x2533318 VA: 0x7594b4b318
	public Void .ctor() { }
}
```