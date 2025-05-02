# ClimbTowerSquadSlotItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _charPanelGo`

- `GameObject _emptyPanelGo`

- `GameObject _displayPanelGo`

- `GameObject _assistPanelGo`

- `Transform _cardContainer`

- `Single _charCardScale`

- `Int32 m_index`

- `Boolean m_isEmpty`

- `Boolean m_isAssist`

- `UICharacterCardPanel m_characterCard`


## Methods

- `Void set_onCardClick(Action`1)`

- `Void set_onClearAssistClick(Action`1)`

- `Void set_onGetAssistClick(Action`1)`

- `Void Render(Int32, CharacterCardViewModel, Boolean)`

- `Void _OnItemClick()`

- `Void OnEmptyClick()`

- `Void OnReplaceAssistClick()`

- `Void OnClearAssistClick()`

- `Void <Render>b__22_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSlotItemView : MonoBehaviour, IHotfixable
{
	private GameObject _charPanelGo; // 0x18
	private GameObject _emptyPanelGo; // 0x20
	private GameObject _displayPanelGo; // 0x28
	private GameObject _assistPanelGo; // 0x30
	private Transform _cardContainer; // 0x38
	private Single _charCardScale; // 0x40
	private Action`1 <onCardClick>k__BackingField; // 0x48
	private Action`1 <onClearAssistClick>k__BackingField; // 0x50
	private Action`1 <onGetAssistClick>k__BackingField; // 0x58
	private Int32 m_index; // 0x60
	private Boolean m_isEmpty; // 0x64
	private Boolean m_isAssist; // 0x65
	private UICharacterCardPanel m_characterCard; // 0x68
	private static DelegateBridge __Hotfix0_get_onCardClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onCardClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onClearAssistClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onClearAssistClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onGetAssistClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onGetAssistClick; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x38
	private static DelegateBridge __Hotfix0_OnEmptyClick; // 0x40
	private static DelegateBridge __Hotfix0_OnReplaceAssistClick; // 0x48
	private static DelegateBridge __Hotfix0_OnClearAssistClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Action`1 onCardClick { get; set; }
	private Action`1 onClearAssistClick { get; set; }
	private Action`1 onGetAssistClick { get; set; }

	// RVA: 0x2cb8760 VA: 0x75952d0760
	private Action`1 get_onCardClick() { }
	// RVA: 0x2cb82d4 VA: 0x75952d02d4
	public Void set_onCardClick(Action`1 value) { }
	// RVA: 0x2cb87c8 VA: 0x75952d07c8
	private Action`1 get_onClearAssistClick() { }
	// RVA: 0x2cb8358 VA: 0x75952d0358
	public Void set_onClearAssistClick(Action`1 value) { }
	// RVA: 0x2cb8830 VA: 0x75952d0830
	private Action`1 get_onGetAssistClick() { }
	// RVA: 0x2cb83dc VA: 0x75952d03dc
	public Void set_onGetAssistClick(Action`1 value) { }
	// RVA: 0x2cb8460 VA: 0x75952d0460
	public Void Render(Int32 position, CharacterCardViewModel cardViewModel, Boolean isAssist) { }
	// RVA: 0x2cb8898 VA: 0x75952d0898
	private Void _OnItemClick() { }
	// RVA: 0x2cb8940 VA: 0x75952d0940
	public Void OnEmptyClick() { }
	// RVA: 0x2cb89a8 VA: 0x75952d09a8
	public Void OnReplaceAssistClick() { }
	// RVA: 0x2cb8a58 VA: 0x75952d0a58
	public Void OnClearAssistClick() { }
	// RVA: 0x2cb8b08 VA: 0x75952d0b08
	public Void .ctor() { }
	// RVA: 0x2cb8b84 VA: 0x75952d0b84
	private Void <Render>b__22_0(Int32 _) { }
}
```