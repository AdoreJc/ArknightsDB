# PluginHandler

**Namespace:** ` `


## Fields

- `StageZoneHomeToDoItem m_closure`


## Methods

- `Void SetMainSprite(Sprite)`

- `ZoneHomeToDoItemModel GetViewModel()`

- `Void SetEndTime(Int64)`

- `Void AttachGraphicsToButton(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PluginHandler : IHotfixable
{
	private StageZoneHomeToDoItem m_closure; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetMainSprite; // 0x8
	private static DelegateBridge __Hotfix0_GetViewModel; // 0x10
	private static DelegateBridge __Hotfix0_SetEndTime; // 0x18
	private static DelegateBridge __Hotfix0_AttachGraphicsToButton; // 0x20


	// RVA: 0x2f04ddc VA: 0x759551cddc
	public Void .ctor(StageZoneHomeToDoItem closure) { }
	// RVA: 0x2f05400 VA: 0x759551d400
	public Void SetMainSprite(Sprite sprite) { }
	// RVA: 0x2f05494 VA: 0x759551d494
	public ZoneHomeToDoItemModel GetViewModel() { }
	// RVA: 0x2f05508 VA: 0x759551d508
	public Void SetEndTime(Int64 endTs) { }
	// RVA: 0x2f05590 VA: 0x759551d590
	public Void AttachGraphicsToButton(List`1 graphics) { }
}
```