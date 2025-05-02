# SquadCardView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `GameObject _panelEmpty`

- `Transform _cardContainer`

- `Single _charCardScaler`

- `UICharacterCardPanel m_characterCard`

- `GameObject m_cardBanObj`

- `Int32 m_indexCache`

- `Boolean m_isEmptyNotClickable`

- `Boolean <isEmpty>k__BackingField`


## Properties

- `Boolean isEmpty`


## Methods

- `Void set_onClick(Action`1)`

- `Boolean get_isEmpty()`

- `Void set_isEmpty(Boolean)`

- `Void RenderCard(Int32, SquadCardViewModel)`

- `Void EventOnClick()`

- `Void _OnClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadCardView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private Transform _cardContainer; // 0x20
	private Single _charCardScaler; // 0x28
	private UICharacterCardPanel m_characterCard; // 0x30
	private GameObject m_cardBanObj; // 0x38
	private Int32 m_indexCache; // 0x40
	private Action`1 m_onClick; // 0x48
	private Boolean m_isEmptyNotClickable; // 0x50
	private Boolean <isEmpty>k__BackingField; // 0x51
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x10
	private static DelegateBridge __Hotfix0_set_isEmpty; // 0x18
	private static DelegateBridge __Hotfix0_RenderCard; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x28
	private static DelegateBridge __Hotfix0__OnClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Action`1 onClick { get; set; }
	public Boolean isEmpty { get; set; }

	// RVA: 0x23c449c VA: 0x75949dc49c
	public Action`1 get_onClick() { }
	// RVA: 0x23c4504 VA: 0x75949dc504
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x23c4588 VA: 0x75949dc588
	public Boolean get_isEmpty() { }
	// RVA: 0x23c45f0 VA: 0x75949dc5f0
	private Void set_isEmpty(Boolean value) { }
	// RVA: 0x23c4670 VA: 0x75949dc670
	public Void RenderCard(Int32 index, SquadCardViewModel viewModel) { }
	// RVA: 0x23c4aa8 VA: 0x75949dcaa8
	public Void EventOnClick() { }
	// RVA: 0x23c4b14 VA: 0x75949dcb14
	private Void _OnClick(Int32 chrInstId) { }
	// RVA: 0x23c4bc8 VA: 0x75949dcbc8
	public Void .ctor() { }
}
```