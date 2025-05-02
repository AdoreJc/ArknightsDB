# UIPortraitChooseCharViewModel

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `String titleText`

- `Int32 selectCount`

- `Int32 enterSequence`


## Properties

- `Boolean isComplete`


## Methods

- `Boolean get_isComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIPortraitChooseCharViewModel : IHotfixable
{
	public const Int32 ENTER_SEQUENCE_DEFAULT; // 0x0
	public String titleText; // 0x10
	public List`1 charCardList; // 0x18
	public List`1 selectCharIdList; // 0x20
	public Int32 selectCount; // 0x28
	public Int32 enterSequence; // 0x2c
	private static DelegateBridge __Hotfix0_get_isComplete; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean isComplete { get; }

	// RVA: 0x2c3df24 VA: 0x7595255f24
	public Boolean get_isComplete() { }
	// RVA: 0x2c3f458 VA: 0x7595257458
	public Void .ctor() { }
}
```