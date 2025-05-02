# Act12sideSquadHomeCharmPluginView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Boolean m_canEdit`


## Methods

- `Single _GetAngle(Single)`

- `Void _TryTriggerAVG()`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideSquadHomeCharmPluginView : SquadHomeCharmPluginView
{
	private List`1 _btnAdds; // 0x30
	private List`1 _charmItems; // 0x38
	private Boolean m_canEdit; // 0x40
	private const Single ROTATE_MIN_ANGLE_1; // 0x0
	private const Single ROTATE_MAX_ANGLE_1; // 0x0
	private const Single ROTATE_MIN_ANGLE_2; // 0x0
	private const Single ROTATE_MAX_ANGLE_2; // 0x0
	private const Single ROTATE_MIN_ANGLE_3; // 0x0
	private const Single ROTATE_MAX_ANGLE_3; // 0x0
	private const Single MIN_DIFF; // 0x0
	private const Int32 RANDOM_TYPE_COUNT; // 0x0
	private readonly Vector3 VIEW_POS; // 0x44
	private const Single INIT_ICON_LOCAL_ROTATE; // 0x0
	private const Single TOLERANCE; // 0x0
	private List`1 m_charmList; // 0x50
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_EventOnEditCharmBtnClick; // 0x10
	private static DelegateBridge __Hotfix0__GetAngle; // 0x18
	private static DelegateBridge __Hotfix0__RefreshCharmsList; // 0x20
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3468848 VA: 0x7595a80848
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x34688ac VA: 0x7595a808ac
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x34694b8 VA: 0x7595a814b8
	public override Void EventOnEditCharmBtnClick() { }
	// RVA: 0x3469338 VA: 0x7595a81338
	private Single _GetAngle(Single lastAngle) { }
	// RVA: 0x3468fac VA: 0x7595a80fac
	private List`1 _RefreshCharmsList(PluginInputParams param) { }
	// RVA: 0x346927c VA: 0x7595a8127c
	private Void _TryTriggerAVG() { }
	// RVA: 0x346959c VA: 0x7595a8159c
	public Void .ctor() { }
	// RVA: 0x3469720 VA: 0x7595a81720
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
}
```