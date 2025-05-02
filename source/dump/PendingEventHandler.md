# PendingEventHandler

**Namespace:** ` `


## Fields

- `RoguelikeDungeonController m_controller`


## Methods

- `Void Init(RoguelikeDungeonController)`

- `Boolean HandleWhenPageResume()`

- `Boolean HandleWhenShopBuy()`

- `Void HandleWhenChoiceSelected(Boolean)`

- `Void _OpenState(Boolean)`

- `Boolean HandleWhenTakeReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PendingEventHandler : IHotfixable
{
	private RoguelikeDungeonController m_controller; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_HandleWhenPageResume; // 0x8
	private static DelegateBridge __Hotfix0_HandleWhenShopBuy; // 0x10
	private static DelegateBridge __Hotfix0_HandleWhenChoiceSelected; // 0x18
	private static DelegateBridge __Hotfix0__OpenState; // 0x20
	private static DelegateBridge __Hotfix0_HandleWhenTakeReward; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2aa83c4 VA: 0x75950c03c4
	public Void Init(RoguelikeDungeonController controller) { }
	// RVA: 0x2aad0a8 VA: 0x75950c50a8
	public Boolean HandleWhenPageResume() { }
	// RVA: 0x2aad1f4 VA: 0x75950c51f4
	public Boolean HandleWhenShopBuy() { }
	// RVA: 0x2aad2b0 VA: 0x75950c52b0
	public Void HandleWhenChoiceSelected(Boolean isFastMode) { }
	// RVA: 0x VA: 0x0
	private Void _OpenState(Boolean isFastMode) { }
	// RVA: 0x2aad4a8 VA: 0x75950c54a8
	public Boolean HandleWhenTakeReward() { }
	// RVA: 0x2aacd04 VA: 0x75950c4d04
	public Void .ctor() { }
}
```