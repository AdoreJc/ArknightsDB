# RoguelikeRewardListViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String topicId`


## Properties

- `Boolean itemFinishFlag`


## Methods

- `Boolean get_itemFinishFlag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardListViewModel : IHotfixable
{
	public List`1 itemList; // 0x10
	public String topicId; // 0x18
	private static DelegateBridge __Hotfix0_get_itemFinishFlag; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean itemFinishFlag { get; }

	// RVA: 0x2a9e47c VA: 0x75950b647c
	public Boolean get_itemFinishFlag() { }
	// RVA: 0x2aa529c VA: 0x75950bd29c
	public Void .ctor() { }
}
```