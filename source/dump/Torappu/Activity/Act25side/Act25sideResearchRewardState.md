# Act25sideResearchRewardState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `SimpleLayoutContent _view`

- `Boolean m_isInited`

- `RewardAdapter m_adpter`

- `Act25sideResearchRewardStateBean m_stateBean`


## Methods

- `Void _UpdateView()`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchRewardState : PopupFloatState, IHotfixable
{
	private SimpleLayoutContent _view; // 0x70
	private Boolean m_isInited; // 0x78
	private RewardAdapter m_adpter; // 0x80
	private Act25sideResearchRewardStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__UpdateView; // 0x10
	private static DelegateBridge __Hotfix0__GenerateItemList; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x327a808 VA: 0x7595892808
	public override IStateBean GetCacheBean() { }
	// RVA: 0x327a870 VA: 0x7595892870
	protected override Void OnEnter() { }
	// RVA: 0x327aa80 VA: 0x7595892a80
	private Void _UpdateView() { }
	// RVA: 0x327ac18 VA: 0x7595892c18
	private List`1 _GenerateItemList(String actId, String areaId) { }
	// RVA: 0x327a8ec VA: 0x75958928ec
	private Void _InitIfNot() { }
	// RVA: 0x327b1fc VA: 0x75958931fc
	public Void .ctor() { }
	// RVA: 0x327b350 VA: 0x7595893350
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```