# RL03TotemListItemViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String topicId`

- `String totemId`

- `RL03TotemViewModel totemViewModel`

- `TotemItemDisplayType displayType`

- `Boolean isSelected`

- `Boolean needHighLight`


## Properties

- `String instId`

- `Boolean isEmpty`

- `Boolean canUseTotem`

- `Boolean isDivination`

- `Boolean isBossTotem`


## Methods

- `String get_instId()`

- `Boolean get_isEmpty()`

- `Boolean get_canUseTotem()`

- `Boolean get_isDivination()`

- `Boolean get_isBossTotem()`

- `String GetTotemFullDesc()`

- `Boolean CheckIsSameTotem(RL03TotemListItemViewModel)`

- `RL03TotemListViewType GetViewType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemListItemViewModel : IRL03TotemListViewModel, IHotfixable
{
	public String topicId; // 0x10
	public String totemId; // 0x18
	public RL03TotemViewModel totemViewModel; // 0x20
	public TotemItemDisplayType displayType; // 0x28
	public Boolean isSelected; // 0x2c
	public Boolean needHighLight; // 0x2d
	private static DelegateBridge __Hotfix0_get_instId; // 0x0
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x8
	private static DelegateBridge __Hotfix0_get_canUseTotem; // 0x10
	private static DelegateBridge __Hotfix0_get_isDivination; // 0x18
	private static DelegateBridge __Hotfix0_get_isBossTotem; // 0x20
	private static DelegateBridge __Hotfix0_GetTotemFullDesc; // 0x28
	private static DelegateBridge __Hotfix0_CheckIsSameTotem; // 0x30
	private static DelegateBridge __Hotfix0_GetViewType; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String instId { get; }
	public Boolean isEmpty { get; }
	public Boolean canUseTotem { get; }
	public Boolean isDivination { get; }
	public Boolean isBossTotem { get; }

	// RVA: 0x2baf20c VA: 0x75951c720c
	public String get_instId() { }
	// RVA: 0x2baf184 VA: 0x75951c7184
	public Boolean get_isEmpty() { }
	// RVA: 0x2baeec4 VA: 0x75951c6ec4
	public Boolean get_canUseTotem() { }
	// RVA: 0x2baf438 VA: 0x75951c7438
	public Boolean get_isDivination() { }
	// RVA: 0x2bafedc VA: 0x75951c7edc
	public Boolean get_isBossTotem() { }
	// RVA: 0x2baf2a8 VA: 0x75951c72a8
	public String GetTotemFullDesc() { }
	// RVA: 0x2bae9b8 VA: 0x75951c69b8
	public Boolean CheckIsSameTotem(RL03TotemListItemViewModel itemViewModel) { }
	// RVA: 0x2bb0b2c VA: 0x75951c8b2c
	public RL03TotemListViewType GetViewType() { }
	// RVA: 0x2bb05c8 VA: 0x75951c85c8
	public Void .ctor() { }
}
```