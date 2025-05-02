# CrisisV2MapKeypointNodeView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `GameObject _unreachGo`

- `GameObject _reachableGo`

- `GameObject _availGo`

- `GameObject _completedGo`

- `GameObject _animHighlightGo`


## Methods

- `Void <>xLuaBaseProxy_PlayHighlightAnimIfNeed(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapKeypointNodeView : CrisisV2MapNodeViewBase
{
	private GameObject _unreachGo; // 0x50
	private GameObject _reachableGo; // 0x58
	private GameObject _availGo; // 0x60
	private GameObject _completedGo; // 0x68
	private GameObject _animHighlightGo; // 0x70
	private static DelegateBridge __Hotfix0_GetSlotType; // 0x0
	private static DelegateBridge __Hotfix0_PlayHighlightAnimIfNeed; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2c04b9c VA: 0x759521cb9c
	public override CrisisV2NodeSlotType GetSlotType() { }
	// RVA: 0x2c04c04 VA: 0x759521cc04
	protected override Void PlayHighlightAnimIfNeed(Boolean isNodeHighlight) { }
	// RVA: 0x2c04c88 VA: 0x759521cc88
	protected override Void Render() { }
	// RVA: 0x2c04df4 VA: 0x759521cdf4
	public Void .ctor() { }
	// RVA: 0x2c04ed0 VA: 0x759521ced0
	private Void <>xLuaBaseProxy_PlayHighlightAnimIfNeed(Boolean P0) { }
}
```