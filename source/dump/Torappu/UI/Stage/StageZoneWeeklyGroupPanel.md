# StageZoneWeeklyGroupPanel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ScrollRect _scrollRect`

- `SimpleLayoutContent _zoneList`

- `WeeklyGroupZoneIconWidget _iconWidget`

- `RectTransform _rtIconToday`

- `Boolean m_hasInited`

- `ZoneGroupViewModel m_zoneGroupModel`

- `Adapter m_adapter`


## Methods

- `Void _UpdateIconWidget()`

- `Void _InitIfNot()`

- `Void OnItemClick(String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnValueChanged(ZoneGroupViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneWeeklyGroupPanel : StageZoneGroupPanel, IHotfixable
{
	private ScrollRect _scrollRect; // 0x60
	private SimpleLayoutContent _zoneList; // 0x68
	private WeeklyGroupZoneIconWidget _iconWidget; // 0x70
	private RectTransform _rtIconToday; // 0x78
	private const Int32 WEEK_COUNT; // 0x0
	private Boolean m_hasInited; // 0x80
	private ZoneGroupViewModel m_zoneGroupModel; // 0x88
	private Adapter m_adapter; // 0x90
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__UpdateIconWidget; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fbf5ac VA: 0x75955d75ac
	protected override Void OnEnter() { }
	// RVA: 0x2fbf728 VA: 0x75955d7728
	private Void _UpdateIconWidget() { }
	// RVA: 0x2fbfb38 VA: 0x75955d7b38
	public override Void OnValueChanged(ZoneGroupViewProperty property) { }
	// RVA: 0x2fbf658 VA: 0x75955d7658
	private Void _InitIfNot() { }
	// RVA: 0x2fbfc70 VA: 0x75955d7c70
	private Void OnItemClick(String zoneId) { }
	// RVA: 0x2fbff34 VA: 0x75955d7f34
	public Void .ctor() { }
	// RVA: 0x2fbffa0 VA: 0x75955d7fa0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2fbffa4 VA: 0x75955d7fa4
	private Void <>xLuaBaseProxy_OnValueChanged(ZoneGroupViewProperty P0) { }
}
```