# Act20sideSquadHomeCartPluginView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Image _imgPartRoof`

- `Image _imgPartFront`

- `Image _imgPartTrunk1`

- `Image _imgPartTrunk2`

- `Image _imgPartOS1`

- `Image _imgPartOS2`

- `Boolean m_canEdit`

- `String m_stageId`

- `Boolean m_canUseCart`

- `Boolean m_isRetro`

- `String m_groupId`


## Methods

- `Void EventOnCartBtnClick()`

- `Void EventOnCartPresentationBtnClick()`

- `Void _TryUpdateLeftArrowStatus(SquadGroupViewModel, String, Boolean)`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`

- `Void <>xLuaBaseProxy_OnSquadGroupChanged(SquadGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideSquadHomeCartPluginView : SquadHomePluginView
{
	private Image _imgPartRoof; // 0x30
	private Image _imgPartFront; // 0x38
	private Image _imgPartTrunk1; // 0x40
	private Image _imgPartTrunk2; // 0x48
	private Image _imgPartOS1; // 0x50
	private Image _imgPartOS2; // 0x58
	private Boolean m_canEdit; // 0x60
	private String m_stageId; // 0x68
	private Boolean m_canUseCart; // 0x70
	private Boolean m_isRetro; // 0x71
	private String m_groupId; // 0x78
	private Dictionary`2 m_cartDict; // 0x80
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x0
	private static DelegateBridge __Hotfix0_OnSquadGroupChanged; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCartBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_EventOnCartPresentationBtnClick; // 0x20
	private static DelegateBridge __Hotfix0__TryUpdateLeftArrowStatus; // 0x28
	private static DelegateBridge __Hotfix0__TryGetCartCompSprite; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x330156c VA: 0x759591956c
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x33015d4 VA: 0x75959195d4
	protected override Void OnSquadGroupChanged(SquadGroupViewModel groupModel) { }
	// RVA: 0x330178c VA: 0x759591978c
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x3301db8 VA: 0x7595919db8
	public Void EventOnCartBtnClick() { }
	// RVA: 0x3301f0c VA: 0x7595919f0c
	public Void EventOnCartPresentationBtnClick() { }
	// RVA: 0x3301678 VA: 0x7595919678
	private Void _TryUpdateLeftArrowStatus(SquadGroupViewModel squadGroupModel, String stageId, Boolean canUseCart) { }
	// RVA: 0x3301c38 VA: 0x7595919c38
	private static Boolean _TryGetCartCompSprite(Dictionary`2 cartComponentsDict, CartAccessoryPos accessoryPos, out Sprite compIcon) { }
	// RVA: 0x33020c8 VA: 0x759591a0c8
	public Void .ctor() { }
	// RVA: 0x3302138 VA: 0x759591a138
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
	// RVA: 0x3302140 VA: 0x759591a140
	private Void <>xLuaBaseProxy_OnSquadGroupChanged(SquadGroupViewModel P0) { }
}
```