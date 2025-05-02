# StageZoneMilestoneButtonHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _zoneMilestoneRoot`

- `StageZoneMilestoneButtonBase m_milestoneButtonCache`

- `UIPageFinder m_uiPageFinder`


## Methods

- `Boolean _TryLoadMilestoneButton(ZoneViewModel)`

- `StageZoneMilestoneButtonType _GetMilestoneButtonType(ZoneViewModel)`

- `String _GetMilestoneButtonPath(StageZoneMilestoneButtonType)`

- `Boolean _CheckSixStarMilestoneAvail(ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneMilestoneButtonHolder : DataBinder`1
{
	private RectTransform _zoneMilestoneRoot; // 0x20
	private StageZoneMilestoneButtonBase m_milestoneButtonCache; // 0x28
	private UIPageFinder m_uiPageFinder; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__TryLoadMilestoneButton; // 0x8
	private static DelegateBridge __Hotfix0__GetMilestoneButtonType; // 0x10
	private static DelegateBridge __Hotfix0__GetMilestoneButtonPath; // 0x18
	private static DelegateBridge __Hotfix0__CheckSixStarMilestoneAvail; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2fb7d84 VA: 0x75955cfd84
	public override Void OnValueChanged(ZoneViewProperty selectedZoneProperty) { }
	// RVA: 0x2fb7e4c VA: 0x75955cfe4c
	private Boolean _TryLoadMilestoneButton(ZoneViewModel selectedZoneModel) { }
	// RVA: 0x2fb8100 VA: 0x75955d0100
	private StageZoneMilestoneButtonType _GetMilestoneButtonType(ZoneViewModel selectedZoneModel) { }
	// RVA: 0x2fb8188 VA: 0x75955d0188
	private String _GetMilestoneButtonPath(StageZoneMilestoneButtonType buttonType) { }
	// RVA: 0x2fb823c VA: 0x75955d023c
	private Boolean _CheckSixStarMilestoneAvail(ZoneViewModel selectedZoneModel) { }
	// RVA: 0x2fb82e0 VA: 0x75955d02e0
	public Void .ctor() { }
}
```