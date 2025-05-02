# RoguelikeExpeditionCommonPluginContext

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject _charCardPrefab`

- `RoguelikeExpeditionSelectingCharView _selectingCharPrefab`

- `String m_cachedSelectDescFormat`


## Methods

- `Int32 _OverrideExpeditionCharListSort(RoguelikeExpeditionCharCardViewModel, RoguelikeExpeditionCharCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExpeditionCommonPluginContext : RoguelikeExpeditionPluginContext
{
	private GameObject _charCardPrefab; // 0x18
	private RoguelikeExpeditionSelectingCharView _selectingCharPrefab; // 0x20
	private String m_cachedSelectDescFormat; // 0x28
	private static DelegateBridge __Hotfix0_get_charCardPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_selectingCharPrefab; // 0x8
	private static DelegateBridge __Hotfix0_get_overrideExpeditionCharListSort; // 0x10
	private static DelegateBridge __Hotfix0__OverrideExpeditionCharListSort; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_GetSelectDesc; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override GameObject charCardPrefab { get; }
	public override RoguelikeExpeditionSelectingCharView selectingCharPrefab { get; }
	public override RoguelikeExpeditionCharListSort overrideExpeditionCharListSort { get; }

	// RVA: 0x2a32420 VA: 0x759504a420
	public override GameObject get_charCardPrefab() { }
	// RVA: 0x2a32488 VA: 0x759504a488
	public override RoguelikeExpeditionSelectingCharView get_selectingCharPrefab() { }
	// RVA: 0x2a324f0 VA: 0x759504a4f0
	public override RoguelikeExpeditionCharListSort get_overrideExpeditionCharListSort() { }
	// RVA: 0x2a326e0 VA: 0x759504a6e0
	private Int32 _OverrideExpeditionCharListSort(RoguelikeExpeditionCharCardViewModel lhs, RoguelikeExpeditionCharCardViewModel rhs) { }
	// RVA: 0x2a327c8 VA: 0x759504a7c8
	public override Void LoadData(String topicId) { }
	// RVA: 0x2a328c0 VA: 0x759504a8c0
	public override String GetSelectDesc(RoguelikeExpeditionCharCardViewModel selectCharModel) { }
	// RVA: 0x2a329c4 VA: 0x759504a9c4
	public Void .ctor() { }
}
```