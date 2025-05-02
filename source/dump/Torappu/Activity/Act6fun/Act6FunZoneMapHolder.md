# Act6FunZoneMapHolder

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _BindPluginEvents(ActivityCustomZoneMap)`

- `Void _TryBindAchieveInfoPluginEvents(ActivityCustomZoneMapBasePlugin)`

- `Void _TryBindBgPluginEvents(ActivityCustomZoneMapBasePlugin)`

- `Void _OnClaimRewardItemClick(String)`

- `Void _OnBgClick()`

- `Void <_OnClaimRewardItemClick>b__6_0(Act6FunReceiveRewardsResponse)`

- `Void <_OnClaimRewardItemClick>b__6_1()`

- `Void <>xLuaBaseProxy__InitZoneMap(ActivityCustomZoneMap)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapHolder : ActivityCustomZoneMapHolderBase
{
	private UIPageFinder m_pageFinder; // 0x60
	private UIStateFinder m_stateFinder; // 0x70
	private static DelegateBridge __Hotfix0__InitZoneMap; // 0x0
	private static DelegateBridge __Hotfix0__BindPluginEvents; // 0x8
	private static DelegateBridge __Hotfix0__TryBindAchieveInfoPluginEvents; // 0x10
	private static DelegateBridge __Hotfix0__TryBindBgPluginEvents; // 0x18
	private static DelegateBridge __Hotfix0__OnClaimRewardItemClick; // 0x20
	private static DelegateBridge __Hotfix0__OnBgClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31b67a4 VA: 0x75957ce7a4
	protected override Void _InitZoneMap(ActivityCustomZoneMap zoneMap) { }
	// RVA: 0x31b6834 VA: 0x75957ce834
	private Void _BindPluginEvents(ActivityCustomZoneMap zoneMap) { }
	// RVA: 0x31b6974 VA: 0x75957ce974
	private Void _TryBindAchieveInfoPluginEvents(ActivityCustomZoneMapBasePlugin plugin) { }
	// RVA: 0x31b6ad8 VA: 0x75957cead8
	private Void _TryBindBgPluginEvents(ActivityCustomZoneMapBasePlugin plugin) { }
	// RVA: 0x31b6c3c VA: 0x75957cec3c
	private Void _OnClaimRewardItemClick(String rewardId) { }
	// RVA: 0x31b6ed4 VA: 0x75957ceed4
	private Void _OnBgClick() { }
	// RVA: 0x31b6f78 VA: 0x75957cef78
	public Void .ctor() { }
	// RVA: 0x31b6fe8 VA: 0x75957cefe8
	private Void <_OnClaimRewardItemClick>b__6_0(Act6FunReceiveRewardsResponse response) { }
	// RVA: 0x31b7160 VA: 0x75957cf160
	private Void <_OnClaimRewardItemClick>b__6_1() { }
	// RVA: 0x31b71f4 VA: 0x75957cf1f4
	private Void <>xLuaBaseProxy__InitZoneMap(ActivityCustomZoneMap P0) { }
}
```