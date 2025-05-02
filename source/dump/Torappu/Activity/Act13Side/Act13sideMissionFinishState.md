# Act13sideMissionFinishState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideFinishMissionView _missionView`

- `Act13sidePrestigePromoteView _promoteView`

- `Transform _container`

- `Act13sideMissionFinishViewModel m_cacheModel`

- `Int32 m_cacheIndex`

- `Int32 m_currentPer`

- `Int32 m_finishPer`

- `Act13sidePrestigePromoteView m_promoteView`

- `String m_actId`


## Methods

- `Void _InitPromoteView()`

- `Void ToNextOrDismiss()`

- `Void _RenderCurrent()`

- `Void <OnEnter>b__12_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionFinishState : PopupFloatState
{
	private Act13sideFinishMissionView _missionView; // 0x70
	private Act13sidePrestigePromoteView _promoteView; // 0x78
	private Transform _container; // 0x80
	private Dictionary`2 m_missionDataGroup; // 0x88
	private Act13sideMissionFinishViewModel m_cacheModel; // 0x90
	private Int32 m_cacheIndex; // 0x98
	private Int32 m_currentPer; // 0x9c
	private Int32 m_finishPer; // 0xa0
	private Act13sidePrestigePromoteView m_promoteView; // 0xa8
	private String m_actId; // 0xb0
	private static DelegateBridge __Hotfix0__InitPromoteView; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_ToNextOrDismiss; // 0x18
	private static DelegateBridge __Hotfix0__RenderCurrent; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x342c84c VA: 0x7595a4484c
	private Void _InitPromoteView() { }
	// RVA: 0x342c950 VA: 0x7595a44950
	public override IStateBean GetCacheBean() { }
	// RVA: 0x342c9b4 VA: 0x7595a449b4
	protected override Void OnEnter() { }
	// RVA: 0x342ce10 VA: 0x7595a44e10
	public Void ToNextOrDismiss() { }
	// RVA: 0x342cccc VA: 0x7595a44ccc
	private Void _RenderCurrent() { }
	// RVA: 0x342cecc VA: 0x7595a44ecc
	public Void .ctor() { }
	// RVA: 0x342cf3c VA: 0x7595a44f3c
	private Void <OnEnter>b__12_0() { }
	// RVA: 0x342cfa4 VA: 0x7595a44fa4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```