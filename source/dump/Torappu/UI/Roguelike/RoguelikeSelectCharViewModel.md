# RoguelikeSelectCharViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeCharCardViewModel lastSelectViewModel`

- `Int32 maxSelectCount`

- `String ticketId`

- `Boolean isSingle`

- `ShowConfig showConfig`


## Methods

- `Void _ConstructDefaultComparers()`

- `Int32 _CompareCharViewModel(RoguelikeCharCardViewModel, RoguelikeCharCardViewModel)`

- `Void _SortCharList(List`1)`

- `Int32 _FindCardSelectIndex(RoguelikeCharCardViewModel)`

- `Void NotifySelectChanged()`

- `RoguelikeSelectCharViewModel AttachPluginContexts(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSelectCharViewModel : IHotfixable
{
	private List`1 m_cardListCache; // 0x10
	private List`1 m_comparers; // 0x18
	public RoguelikeCharCardViewModel lastSelectViewModel; // 0x20
	public Int32 maxSelectCount; // 0x28
	public String ticketId; // 0x30
	public Boolean isSingle; // 0x38
	public ShowConfig showConfig; // 0x39
	public List`1 viewModelList; // 0x40
	public List`1 selectInstId; // 0x48
	private static DelegateBridge __Hotfix0_get_sortedCardListCache; // 0x0
	private static DelegateBridge __Hotfix0__ConstructDefaultComparers; // 0x8
	private static DelegateBridge __Hotfix0__CompareCharViewModel; // 0x10
	private static DelegateBridge __Hotfix0__SortCharList; // 0x18
	private static DelegateBridge __Hotfix0__FindCardSelectIndex; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge __Hotfix0_NotifySelectChanged; // 0x30
	private static DelegateBridge __Hotfix0_AttachPluginContexts; // 0x38

	public List`1 sortedCardListCache { get; }

	// RVA: 0x2acf758 VA: 0x75950e7758
	public List`1 get_sortedCardListCache() { }
	// RVA: 0x2ad1c18 VA: 0x75950e9c18
	private Void _ConstructDefaultComparers() { }
	// RVA: 0x2ad26d8 VA: 0x75950ea6d8
	private Int32 _CompareCharViewModel(RoguelikeCharCardViewModel lhs, RoguelikeCharCardViewModel rhs) { }
	// RVA: 0x2ad1a1c VA: 0x75950e9a1c
	private Void _SortCharList(List`1 charList) { }
	// RVA: 0x2ad1b14 VA: 0x75950e9b14
	private Int32 _FindCardSelectIndex(RoguelikeCharCardViewModel cardModel) { }
	// RVA: 0x2ad0cac VA: 0x75950e8cac
	public Void .ctor() { }
	// RVA: 0x2ac5cd0 VA: 0x75950ddcd0
	public Void NotifySelectChanged() { }
	// RVA: 0x2ad1044 VA: 0x75950e9044
	public RoguelikeSelectCharViewModel AttachPluginContexts(List`1 pluginContexts) { }
}
```