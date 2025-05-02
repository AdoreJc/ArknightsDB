# RL02ExpeditionPluginContext

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `GameObject _charCardPrefab`

- `RL02ExpeditionSelectingCharView _selectingCharPrefab`

- `RL02ExpeditionPluginModel m_viewModel`


## Methods

- `RoguelikeCharBuffModel GetCharBuff(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02ExpeditionPluginContext : RoguelikeExpeditionPluginContext
{
	private GameObject _charCardPrefab; // 0x18
	private RL02ExpeditionSelectingCharView _selectingCharPrefab; // 0x20
	private RL02ExpeditionPluginModel m_viewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_charCardPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_selectingCharPrefab; // 0x8
	private static DelegateBridge __Hotfix0_get_overrideExpeditionCharListSort; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_GetSelectDesc; // 0x20
	private static DelegateBridge __Hotfix0_GetCharBuff; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override GameObject charCardPrefab { get; }
	public override RoguelikeExpeditionSelectingCharView selectingCharPrefab { get; }
	public override RoguelikeExpeditionCharListSort overrideExpeditionCharListSort { get; }

	// RVA: 0x2b6a7fc VA: 0x75951827fc
	public override GameObject get_charCardPrefab() { }
	// RVA: 0x2b6a864 VA: 0x7595182864
	public override RoguelikeExpeditionSelectingCharView get_selectingCharPrefab() { }
	// RVA: 0x2b6a8cc VA: 0x75951828cc
	public override RoguelikeExpeditionCharListSort get_overrideExpeditionCharListSort() { }
	// RVA: 0x2b6a984 VA: 0x7595182984
	public override Void LoadData(String topicId) { }
	// RVA: 0x2b6ad00 VA: 0x7595182d00
	public override String GetSelectDesc(RoguelikeExpeditionCharCardViewModel selectCharModel) { }
	// RVA: 0x2b6a6d4 VA: 0x75951826d4
	public RoguelikeCharBuffModel GetCharBuff(String charInstId) { }
	// RVA: 0x2b6af40 VA: 0x7595182f40
	public Void .ctor() { }
}
```