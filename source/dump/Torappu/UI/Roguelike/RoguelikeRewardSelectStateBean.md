# RoguelikeRewardSelectStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRewardItemViewModel viewModel`

- `String topicId`

- `Boolean showSeparator`

- `Boolean _isForMapPreview`


## Properties

- `Boolean isForMapPreview`


## Methods

- `Boolean get_isForMapPreview()`

- `Void set_isForMapPreview(Boolean)`

- `Void CheckBtnHideForItemsForPreview()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardSelectStateBean : IStateBean, IHotfixable
{
	public RoguelikeRewardItemViewModel viewModel; // 0x10
	public String topicId; // 0x18
	public Boolean showSeparator; // 0x20
	private Boolean _isForMapPreview; // 0x21
	private static DelegateBridge __Hotfix0_get_isForMapPreview; // 0x0
	private static DelegateBridge __Hotfix0_set_isForMapPreview; // 0x8
	private static DelegateBridge __Hotfix0_CheckBtnHideForItemsForPreview; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean isForMapPreview { get; set; }

	// RVA: 0x2a90ca4 VA: 0x75950a8ca4
	public Boolean get_isForMapPreview() { }
	// RVA: 0x2a90680 VA: 0x75950a8680
	public Void set_isForMapPreview(Boolean value) { }
	// RVA: 0x2a90d14 VA: 0x75950a8d14
	private Void CheckBtnHideForItemsForPreview() { }
	// RVA: 0x2a90ee0 VA: 0x75950a8ee0
	public Void .ctor() { }
}
```