# RL04DungeonDisasterModule

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04DisasterToastView _toastPrefab`

- `RL04DungeonDisasterEffect _disasterEffect`

- `RL04DungeonDisasterEffect m_disasterEffect`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _OnDisasterPushMsg(Object)`

- `Void _TryToNotify(RoguelikeOnDisastersChangedToastArgs, RoguelikeModule, RoguelikeDungeonController)`

- `Void _RefreshEffect()`

- `Void _PlayDisasterStartEffect()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnReloadDungeon()`

- `Void <>xLuaBaseProxy_OnStateChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04DungeonDisasterModule : RoguelikeDungeonModule
{
	private RL04DisasterToastView _toastPrefab; // 0x28
	private RL04DungeonDisasterEffect _disasterEffect; // 0x30
	private RL04DungeonDisasterEffect m_disasterEffect; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnReloadDungeon; // 0x8
	private static DelegateBridge __Hotfix0_OnStateChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnDisasterPushMsg; // 0x18
	private static DelegateBridge __Hotfix0__TryToNotify; // 0x20
	private static DelegateBridge __Hotfix0__RefreshEffect; // 0x28
	private static DelegateBridge __Hotfix0__PlayDisasterStartEffect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2b1657c VA: 0x759512e57c
	protected override Void OnCreate() { }
	// RVA: 0x2b16a30 VA: 0x759512ea30
	protected override Void OnReloadDungeon() { }
	// RVA: 0x2b16a98 VA: 0x759512ea98
	protected override Void OnStateChanged() { }
	// RVA: 0x2b16b70 VA: 0x759512eb70
	private Void _OnDisasterPushMsg(Object arg) { }
	// RVA: 0x2b16dcc VA: 0x759512edcc
	private Void _TryToNotify(RoguelikeOnDisastersChangedToastArgs msg, RoguelikeModule roguelikeModule, RoguelikeDungeonController controller) { }
	// RVA: 0x2b167fc VA: 0x759512e7fc
	private Void _RefreshEffect() { }
	// RVA: 0x2b17254 VA: 0x759512f254
	private Void _PlayDisasterStartEffect() { }
	// RVA: 0x2b173fc VA: 0x759512f3fc
	public Void .ctor() { }
	// RVA: 0x2b1746c VA: 0x759512f46c
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2b17474 VA: 0x759512f474
	private Void <>xLuaBaseProxy_OnReloadDungeon() { }
	// RVA: 0x2b1747c VA: 0x759512f47c
	private Void <>xLuaBaseProxy_OnStateChanged() { }
}
```