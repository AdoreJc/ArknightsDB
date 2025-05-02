# BuildingUIResMenu

**Namespace:** `Torappu.Building.UI`


## Fields

- `BuildingUIResItem _itemGold`

- `BuildingUIResItem _itemElectric`

- `BuildingUIResItem _itemLabor`

- `BuildingUIResItem _itemDmdShd`

- `BuildingUIResItem _itemDiamond`

- `BuildingUIResItem _itemSocialPt`

- `BuildingUIResItem _itemMiscItems`

- `IconConfig _iconManufact`

- `IconConfig _iconShop`

- `IconConfig _iconSocialPt`

- `RectTransform _flyIconsContainer`

- `BuildingLaborDetailView _laborDetail`

- `BuildingLaborViewModel m_laborModel`

- `Status m_overrideStatus`

- `Status m_curStatus`

- `Status m_prevStatus`


## Methods

- `Void NotifySettleRequest(AsyncSettleInfo)`

- `Void DoSettleEffectsImmediately(List`1)`

- `Void DoSettleEffectsImmediately(SyncSettleInfo)`

- `Void ClearAllEffects()`

- `Void FixedUpdate()`

- `Void _OnPlayerDataChanged(Object)`

- `Void EventOnLaborDetailClicked()`

- `Void _LoadData()`

- `Void _Render()`

- `Void _ShowCountEffects(Int32)`

- `Void _ShowAsyncSettleNotifications()`

- `Void _ShowItemFlyEffects(FlyEffectType)`

- `Void _StartFlyItemEffect(RoomType, ItemType, Vector2)`

- `BuildingUIResItem _GetMenuItemByType(ItemType)`

- `Void _TriggerAsyncSettleVoices()`

- `Void _PlaySettleVoices(Boolean, Boolean)`

- `Void <OnStart>b__31_0(BuildingLaborViewModel)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingUIResMenu : PageSingleComponent
{
	private const Single NOTIFY_INTERVAL; // 0x0
	private const String FLY_ITEM_OBJECT_NAME; // 0x0
	private const Single FLY_ANIM_FADE_DUR; // 0x0
	private const Single FLY_ANIM_WAIT_MAX_DUR; // 0x0
	private const Single FLY_ANIM_DUR; // 0x0
	private BuildingUIResItem _itemGold; // 0x20
	private BuildingUIResItem _itemElectric; // 0x28
	private BuildingUIResItem _itemLabor; // 0x30
	private BuildingUIResItem _itemDmdShd; // 0x38
	private BuildingUIResItem _itemDiamond; // 0x40
	private BuildingUIResItem _itemSocialPt; // 0x48
	private BuildingUIResItem _itemMiscItems; // 0x50
	private IconConfig _iconManufact; // 0x58
	private IconConfig _iconShop; // 0x68
	private IconConfig _iconSocialPt; // 0x78
	private RectTransform _flyIconsContainer; // 0x88
	private BuildingLaborDetailView _laborDetail; // 0x90
	private BuildingLaborViewModel m_laborModel; // 0x98
	private Status m_overrideStatus; // 0xa0
	private Status m_curStatus; // 0xb8
	private Status m_prevStatus; // 0xd0
	private List`1 m_asyncSettleRequests; // 0xe8
	private static DelegateBridge __Hotfix0_NotifySettleRequest; // 0x0
	private static DelegateBridge __Hotfix0_DoSettleEffectsImmediately; // 0x8
	private static DelegateBridge __Hotfix1_DoSettleEffectsImmediately; // 0x10
	private static DelegateBridge __Hotfix0_ClearAllEffects; // 0x18
	private static DelegateBridge __Hotfix0_OnStart; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x30
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x38
	private static DelegateBridge __Hotfix0_EventOnLaborDetailClicked; // 0x40
	private static DelegateBridge __Hotfix0__LoadData; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x50
	private static DelegateBridge __Hotfix0__ShowCountEffects; // 0x58
	private static DelegateBridge __Hotfix0__ShowAsyncSettleNotifications; // 0x60
	private static DelegateBridge __Hotfix0__ShowItemFlyEffects; // 0x68
	private static DelegateBridge __Hotfix0__StartFlyItemEffect; // 0x70
	private static DelegateBridge __Hotfix0__GetMenuItemByType; // 0x78
	private static DelegateBridge __Hotfix0__TriggerAsyncSettleVoices; // 0x80
	private static DelegateBridge __Hotfix0__PlaySettleVoices; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x3d3f608 VA: 0x7596357608
	public Void NotifySettleRequest(AsyncSettleInfo settleInfo) { }
	// RVA: 0x3d3f764 VA: 0x7596357764
	public Void DoSettleEffectsImmediately(List`1 settleInfos) { }
	// RVA: 0x3d40324 VA: 0x7596358324
	public Void DoSettleEffectsImmediately(SyncSettleInfo settleInfo) { }
	// RVA: 0x3d404ac VA: 0x75963584ac
	public Void ClearAllEffects() { }
	// RVA: 0x3d40554 VA: 0x7596358554
	protected override Void OnStart() { }
	// RVA: 0x3d40a44 VA: 0x7596358a44
	protected override Void OnDestroy() { }
	// RVA: 0x3d40c1c VA: 0x7596358c1c
	private Void FixedUpdate() { }
	// RVA: 0x3d40c90 VA: 0x7596358c90
	private Void _OnPlayerDataChanged(Object _) { }
	// RVA: 0x3d41438 VA: 0x7596359438
	public Void EventOnLaborDetailClicked() { }
	// RVA: 0x3d40754 VA: 0x7596358754
	private Void _LoadData() { }
	// RVA: 0x3d40880 VA: 0x7596358880
	private Void _Render() { }
	// RVA: 0x3d40de8 VA: 0x7596358de8
	private Void _ShowCountEffects(Int32 miscCountOverride) { }
	// RVA: 0x3d410a4 VA: 0x75963590a4
	private Void _ShowAsyncSettleNotifications() { }
	// RVA: 0x3d41674 VA: 0x7596359674
	private Void _ShowItemFlyEffects(FlyEffectType type) { }
	// RVA: 0x3d3fb20 VA: 0x7596357b20
	private Void _StartFlyItemEffect(RoomType roomId, ItemType itemType, Vector2 anchorOnScreen) { }
	// RVA: 0x3d400e0 VA: 0x75963580e0
	private BuildingUIResItem _GetMenuItemByType(ItemType itemType) { }
	// RVA: 0x3d40f58 VA: 0x7596358f58
	private Void _TriggerAsyncSettleVoices() { }
	// RVA: 0x3d401a8 VA: 0x75963581a8
	private Void _PlaySettleVoices(Boolean manufactReceived, Boolean shopReceived) { }
	// RVA: 0x3d41848 VA: 0x7596359848
	public Void .ctor() { }
	// RVA: 0x3d419b8 VA: 0x75963599b8
	private Void <OnStart>b__31_0(BuildingLaborViewModel _) { }
	// RVA: 0x3d41a10 VA: 0x7596359a10
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x3d41a18 VA: 0x7596359a18
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```