# DeckBranchController

**Namespace:** ` `


## Fields

- `UISwitchTween m_validTween`

- `UISwitchTween m_invalidTween`

- `UISwitchTween m_itemTween`

- `UISwitchTween m_emptyTween`

- `UISwitchTween m_moveTween`

- `SandboxV2ItemCard m_itemCard`

- `UIItemViewModel m_cachedViewModel`


## Methods

- `Void Render(UIItemViewModel, Boolean)`

- `Void _ItemClickEvent(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DeckBranchController : IHotfixable
{
	private UISwitchTween m_validTween; // 0x10
	private UISwitchTween m_invalidTween; // 0x18
	private UISwitchTween m_itemTween; // 0x20
	private UISwitchTween m_emptyTween; // 0x28
	private UISwitchTween m_moveTween; // 0x30
	private SandboxV2ItemCard m_itemCard; // 0x38
	private UIItemViewModel m_cachedViewModel; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__ItemClickEvent; // 0x10


	// RVA: 0x24c352c VA: 0x7594adb52c
	public Void .ctor(DeckBranch branch, SandboxV2ItemCard itemPrefab, Single itemScale) { }
	// RVA: 0x24c3370 VA: 0x7594adb370
	public Void Render(UIItemViewModel item, Boolean skipAnimation) { }
	// RVA: 0x24c3c60 VA: 0x7594adbc60
	private Void _ItemClickEvent(Int32 _) { }
}
```