# UIBattleSandboxConstructMenuItemList

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `ShowType _showType`

- `Transform _costRoot`

- `Transform _repairCostRoot`

- `Transform _repairWhenUpgradeRoot`

- `Transform _notUnlockRoot`

- `Color _normalColor`

- `Color _warningColor`

- `Single _matColorAlpha`

- `SimpleLayoutContent _costLayout`

- `Image _costBg`

- `Text _repairText`

- `Image _repairBg`

- `Text _notUnlockText`

- `Image _repairWhenUpgradeBg`

- `Text _repairWhenUpgradeText`

- `Button _btn`

- `Image _btnIcon`

- `Sprite _iconValid`

- `Sprite _iconNotValid`

- `PairListAdapter m_costAdapter`


## Methods

- `Void Init()`

- `Void Render(BattleSandboxConstructItemListModel)`

- `Void _HideAll()`

- `Void _UpdateNormalList(BattleSandboxConstructItemListModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstructMenuItemList : MonoBehaviour, IHotfixable
{
	private ShowType _showType; // 0x18
	private Transform _costRoot; // 0x20
	private Transform _repairCostRoot; // 0x28
	private Transform _repairWhenUpgradeRoot; // 0x30
	private Transform _notUnlockRoot; // 0x38
	private Color _normalColor; // 0x40
	private Color _warningColor; // 0x50
	private Single _matColorAlpha; // 0x60
	private SimpleLayoutContent _costLayout; // 0x68
	private Image _costBg; // 0x70
	private Text _repairText; // 0x78
	private Image _repairBg; // 0x80
	private Text _notUnlockText; // 0x88
	private Image _repairWhenUpgradeBg; // 0x90
	private Text _repairWhenUpgradeText; // 0x98
	private Button _btn; // 0xa0
	private Image _btnIcon; // 0xa8
	private Sprite _iconValid; // 0xb0
	private Sprite _iconNotValid; // 0xb8
	private PairListAdapter m_costAdapter; // 0xc0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__HideAll; // 0x10
	private static DelegateBridge __Hotfix0__UpdateNormalList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20c004c VA: 0x75946d804c
	public Void Init() { }
	// RVA: 0x20c02cc VA: 0x75946d82cc
	public Void Render(BattleSandboxConstructItemListModel model) { }
	// RVA: 0x20c01f8 VA: 0x75946d81f8
	private Void _HideAll() { }
	// RVA: 0x20c0754 VA: 0x75946d8754
	private Void _UpdateNormalList(BattleSandboxConstructItemListModel model) { }
	// RVA: 0x20c085c VA: 0x75946d885c
	public Void .ctor() { }
}
```